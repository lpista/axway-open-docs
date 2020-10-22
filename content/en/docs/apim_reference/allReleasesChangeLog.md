{
"title": "API Management release change log",
"linkTitle": "Release change log",
"weight":"90",
"date": "2020-10-20",
"description": "Functionality change log for all supported versions of API Gateway, API Manager, and API Portal since version 7.5.3."
}

This page lists the major changes made in each release of API Gateway, API Manager, and API Portal. This is a reference information to help you to decided the best strategy to migrate your product to the latest API Management release

## Version 7.7.20200930

| Version | Highlights | Important changes | Deprecated features | Release Date |
|---------|------------|-------------------|---------------------|--------------|
| [7.7.20200930](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200930_apimgr_relnotes/) {#7.7.20200930} | - API Manager Remote Hosts aligned with PolicyStudio functionality- YAML-based configuration store (Technical preview)- Database integration updates- User membership in multiple organizations- New API Management REST API version 1.4 | - OpenJDK JRE update to v8u265- Changes to the way API Gateway verifies wildcarded certificates- Removed broken and risky algorithms from sFTP server- The Groovy version used by the Scripting Filter is updated to 2.5.13 | - API Management REST APIs, versions 1.1 and 1.2 are now marked as deprecated- Swagger version 1.1 is deprecated- The requirement to run update-apimanager.py has been removed from the Upgrade steps | 30/09/2020 |

## Version 7.7.20200730

| [7.7.20200730](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200730_apimgr_relnotes/) {#7.7.20200730} | | - ICAP filter improvements- Improved upgrade instructions- MSSQL Database Support| | 30/07/2020 |  

## Version 7.7.20200530

| [7.7.20200530](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200530_apimgr_relnotes/) {#7.7.20200530} | - Updated OS Support- Improved upgrade experience | - Log4j file format changed to YAML- Swagger parser libs updated | | 30/05/2020 |

## Version 7.7.20200330

| [7.7.20200330](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200330_apimgr_relnotes/) {#7.7.20200330} | - Added TLS 1.3 support | - OpenSSL updated to v1.1.1 | - FIPS support was removed- The following embedded antivirus scanners will be removed: McAfee Sophos Clam AV | 30/03/2020 |

## Version 7.7.20200130

| [7.7.20200130](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200130_apimgr_relnotes/) {#7.7.20200130} | - Swagger 2.0 enhancements- Open API Specification (OAS) 3.0 enhancements- Try it improvements- Usage tracking improvements- Back-end API improvements- API documentation enhancements- Multi organization (beta) | - Increased validation of WSDLs- Filebeat updated to v6.2.2- Increased validation of /users endpoint- Undesirable cipher suites disabled bu default when using SSL/TLS- Endpoint identification algorithms for LDAPS enabled by default- Fields that contain confidential information are no longer returned in some API calls | - API Tester was removed from instalation- RAML support was removed- Export of back-end APIs is not supported for OAS3 or WSDL APIs- Documentation is no longer provided in PDF format | 30/01/2020 |  

## Version 7.7 SP2

| [7.7 SP2](https://delivery.axway.int/GUI/file/GUI_file_readme.php?3i3aljnfkbsu3pn69e0s7ga307&fileId=74993&readmeId=38812&pdtId=394) {#7.7SP2} | | - OpenSSL updated to 1.0.2t-fips to fix security vulnerabilities | | 21/12/2019 |

## Version 7.7 SP1

| [7.7 SP1](https://delivery.axway.int/GUI/file/GUI_file_readme.php?3i3aljnfkbsu3pn69e0s7ga307&fileId=73780&readmeId=38290&pdtId=394) {#7.7SP1} | | | | 29/08/2019 |

## Version 7.7

| [7.7](https://axway-open-docs.netlify.app/docs/apim_relnotes/201904_release/) {#7.7} | - Subscription licensing for API Management | - Traffic monitor enhancements- Filter JMS transactions by custom property in Traffic Monitor- Entity Explorer added to API Gateway client tools installer- Elastic topology container deployment enhancements | - Support for MySQL Server 2005 has been removed | 12/04/2019 |

## Version 7.6.2 SP5

| [7.6.2 SP5](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=76798&readmeId=39732&pdtId=394) {#7.6.2SP5} | | - The jre directory in Policy Studio/Configuration Studio must be remove before applying the Service Pack | | 17/07/2020 |

## Version 7.6.2 SP4

| [7.6.2 SP4](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=73574&readmeId=38165&pdtId=394) {#7.6.2SP4} | | - JQuery upadated to 3.4.0 to fix security vulnerabilities | | 19/07/2019 |

## Version 7.6.2 SP3

| [7.6.2 SP3](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=72882&readmeId=37699&pdtId=394) {#7.6.2SP3} | | - jQuery updated to 3.3.1 to fix security vulnerabilities- JRE updated to 1.8.0_202 to fix security vulnerabilities | | 18/04/2019 |

## Version 7.6.2 SP2

| [7.6.2 SP2](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=71828&readmeId=37215&pdtId=394) {#7.6.2SP2} | | | | 17/12/2018 |

## Version 7.6.2 SP1

| [7.6.2 SP1](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=71453&readmeId=36940&pdtId=394) {#7.6.2SP1} | | - Spring framework updated to 4.3.18.RELEASE to fix security vulnerabilities- OpenSSL updated to 1.0.2p-fips to fix security vulnerabilities- Bouncy Castle library updated to 1.60 to fix security vulnerabilities | | 01/11/2018 |

## Version 7.6.2

| [7.6.2](https://docs.axway.com/bundle/APIGateway_762_ReleaseNotes_allOS_en_HTML5/page/Content/ReleaseNotesPortal/APIGateway_ReleaseNotes_allOS_en.htm) {#7.6.2} | - Elastic topology container deployment- Smooth rate limiting | - Support for /tmp directory mounted with noexec- Apache Cassandra has been upgraded to version 2.2.12 | - Axway physical appliance deployment option was removed- API Gateway Server support for Windows servers was removed- The ConnectToUrlFilter.removePreviousConnections system property is no longer available. | 26/07/2018 |

## Version 7.5.3 SP13

| [7.5.3 SP13](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=76137&readmeId=39449&pdtId=394) {#7.5.3SP13} | | - Dojo updated to 1.10.10 to fix security vulnerability | | 01/05/2020 |

## Version 7.5.3 SP12

| Version [7.5.3 SP12](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=74514&readmeId=38555&pdtId=394) {#7.5.3SP12} | - Improvements in the XML redaction | - Jackson-databind updated to 2.9.10 to fix security vulnerabilities. | | 26/102019 |

## Version 7.5.3 SP11

| [7.5.3 SP11](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=73425&readmeId=38063&pdtId=394) {#7.5.3SP11} | - The Gateway now includes Zulu OpenJDK 1.8 JRE instead of Oracle JRE 1.8- It is possible to allow inbound API requests with trailing slash to match an API path with no trailing slash- An API method's Content-Type is now checked against the API method's defined MIME type when performing path matching | - OpenSSL updated to 1.0.2r-fips- Added CSRF token protection for API Gateway Management APIs- JQuery updated to 3.4.0 | - To allow legacy API method matching excluding the method's defined MIME type, the Java property com.coreapireg.apimethod.contenttype.legacy must be set to true | 25/06/2019 |

## Version 7.5.3 SP10

| [7.5.3 SP10](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=72293&readmeId=37499&pdtId=394) {#7.5.3SP10} | | - Jython updated to  2.7.1 to fix this security vulnerability- jQuery updated to 3.3.1 to fix this security vulnerability- JRE updated to 1.8.0_202 to fix this security vulnerability |-  Internet Explorer versions 8.0 and 9.0 are no longer officially supported by API Gateway | 22/02/2019 |

## Version 7.5.3 SP9

| [7.5.3 SP9](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=71603&readmeId=37068&pdtId=394) {#7.5.3SP9} | | - IBM MQ updated to 7.5.0.8 to fix this security vulnerability- OpenSSL updated to 1.0.2p-fips to fix this security vulnerability- JRE updated to 1.8.0_191-b12 to fix this security vulnerability- apimanager-promote script now requires decryption password or passfile | | 16/11/2018 |

## Version 7.5.3 SP8

| [7.5.3 SP8](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=70731&readmeId=36410&pdtId=394) {#7.5.3SP8} | | - Bouncy Castle library updated to 1.60 to fix this security vulnerability- Spring framework updated to 4.3.17.RELEASE to fix this security vulnerability- JRE updated to 8u181 to fix this security vulnerability | | 23/08/2018 |

## Version 7.5.3 SP7

| [7.5.3 SP7](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=69650&readmeId=35691&pdtId=394) {#7.5.3SP7} | | - Jackson-databind updated to 2.9.5 to fix this security vulnerability- JRE updated to 8u172 to fix this security vulnerability- OpenSSL updated to 1.0.2o to fix this security vulnerability. | | 08/06/2018 |

## Version 7.5.3 SP6

| [7.5.3 SP6](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=68637&readmeId=35129&pdtId=394) {#7.5.3SP6} | | - OpenSSL updated to v1.0.2.n to fix security vulnerability- Apache Log4j updated to 2.8.2 to fix security vulnerability- When exporting API collections from API Manager, the generated file is now encrypted and not plainText. | | 27/04/2018 |

## Version 7.5.3 SP5

| [7.5.3 SP5](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=68215&readmeId=34904&pdtId=394) {#7.5.3SP5} | | - OpenSSL updated to 1.0.2m-fips to fix security vulnerability- JQuery updated to 2.2.4, to fix security vulnerability- commons-email updated to 1.5 to fix security vulnerability | | 23/01/2018 |

## Version 7.5.3 SP4

| [7.5.3 SP4](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=67207&readmeId=34311&pdtId=394) {#7.5.3SP4} | | - Nimbus JOSE+JWT library updated to v4.41.2 to fix security vulnerability- JRE version updated to v1.8u152 to fix security vulnerability | | 06/11/2017 |

## Version 7.5.3 SP3

| [7.5.3 SP3](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=66867&readmeId=34191&pdtId=394) {#7.5.3SP3} | | | | 02/10/2017 |

## Version 7.5.3 SP2

| [7.5.3 SP2](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=66298&readmeId=33893&pdtId=394) {#7.5.3SP2} | | - JSCH update to 0.1.54 to fix security vulnerabilities | | 31/07/2017 |

## Version 7.5.3 SP1

| [7.5.3 SP1](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=65525&readmeId=33421&pdtId=394) {#7.5.3SP1} | | - JRE updated to v8u131 to fix security vulnerability | | 15/06/2017 |

## Version 7.5.3

| [7.5.3](https://docs.axway.com/bundle/APIGateway_753_ReleaseNotes_allOS_en_HTML5/page/Content/ReleaseNotesPortal/APIGateway_ReleaseNotes_allOS_en.htm) {#7.5.3} | | - Apache ActiveMQ updated to 5.14.3 to fix security vulnerabilities- JSCH update to 0.1.54 to fix security vulnerabilities- owasp esapi updated to 2.1.0.1 to fix security vulnerabilities- JRE updated to 8u121 to fix security vulnerabilities- xmlsec updated to 1.5.8 to fix security vulnerabilities- spring-core updated to v4.3.5 to fix security vulnerabilities- Jsch dependency updated v0.1.54  to fix security vulnerabilities- Remove Fluent-hc dependency from API Gateway | - Sun Access Manager filters have been deprecated and will be removed in a future release- API Gateway Analytics is deprecated and will be removed in a future release>br>- The OpenID connect filters in Policy Studio have been deprecated and will be removed in a future release- Support for Tivoli Access Manager version 6.0 has been removed and replaced by support for Tivoli Access Manager version version 6.1.- The ISO format for API Gateway virtual appliance has been replaced by the OVA format- The jabber and restJabber code samples had been removed | 11/04/2017 |
