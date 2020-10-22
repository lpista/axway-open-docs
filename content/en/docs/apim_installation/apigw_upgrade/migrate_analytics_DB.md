# How to migrate the Analytics Database
This page describe the steps need to migrate the Analytics Database to another Database

1. Do not configure previously the new Gateway to use metrics.
2. Create the new Analytics Database
Ex: in MySQL DB, you can use, CREATE DATABASE <DatabaseName>;
3. Stop the old API Gateway and Analytics (or stop the connection to the Analytics Database)
4. Create a dump to a file of the Analytics database, including data and schema creation statements
Ex: For MySQL DB you could use, mysqldump, 
mysqldump [options] <AnalyticsDBName> --complete-insert --flush-logs --no-create-db --result-file=<filename>.sql   
5. On the sql dump file created in Step 4, look for the table with name, **versions**, and in the insert statements, substitute the value for **DomainID**, with the value for the new installation.
The DomainID value can be found at, *<INSTALL_DIR>/system/conf/nodemanager.xml*, in the attribute, **domainID**.
6. Reload the sql dump file create on Step 3 into the database created in Step 2
Ex: For MySQL DB,  mysql <Database Name From Step 2> < <Sql file created in Step 4>
7. Configure the new Analytics to connect to the Database created in step 2, by running, *<INSTALL_DIR>/analytics/posix/bin/configureserver*
8. Start the new Analytics and verify the data from the old instalation was imported
9. Configure the new Gateway to use metrics, using managedomain, using the metrics database created on Step 2
10. Start the new Gateway and  validate that new metrics data are available.
