### [Version 7.7.20200930](#7.7.20200930)
### [Version 7.7.20200730](#7.7.20200730)
### [Version 7.7.20200530](#7.7.20200530)
### [Version 7.7.20200330](#7.7.20200330)
### [Version 7.7.20200130](#7.7.20200130)
### [Version 7.7 SP2](#7.7SP2)
### [Version 7.7 SP1]({#7.7SP1)
### [Version 7.7](#7.7)
### [Version 7.6.2 SP5](#7.6.2SP5)
### [Version 7.6.2 SP3](#7.6.2SP3)
### [Version 7.6.2 SP2](#7.6.2SP2)
### [Version 7.6.2 SP1](#7.6.2SP1)
### [Version 7.6.2](#7.6.2)
### [Version 7.5.3 SP13](#7.5.3SP13)
### [Version 7.5.3 SP12](#7.5.3SP12)
### [Version 7.5.3 SP11](#7.5.3SP11)
### [Version 7.5.3 SP10](#7.5.3SP10)
### [Version 7.5.3 SP9](#7.5.3SP9)
### [Version 7.5.3 SP8](#7.5.3SP8)
### [Version 7.5.3 SP7](#7.5.3SP7)
### [Version 7.5.3 SP6](#7.5.3SP6)
### [Version 7.5.3 SP5](#7.5.3SP5)
### [Version 7.5.3 SP4](#7.5.3SP4)
### [Version 7.5.3 SP3](#7.5.3SP3)
### [Version 7.5.3](#7.5.3)
### [Version 7.5.3 SP2](#7.5.3SP2)
### [Version 7.5.3 SP1](#7.5.3SP1)
---------------
## Version [7.7.20200930](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200930_apimgr_relnotes/) {#7.7.20200930}
### Highlights
* API Manager Remote Hosts aligned with PolicyStudio functionality
* YAML-based configuration store (Technical preview)
* Database integration updates
* User membership in multiple organizations
* New API Management REST API version 1.4
* 29 issues fixed
### Important changes
* OpenJDK JRE update to v8u265
* Changes to the way API Gateway verifies wildcarded certificates
* Removed broken and risky algorithms from sFTP server
* The Groovy version used by the Scripting Filter is updated to 2.5.13
### Deprecated features
* API Management REST APIs, versions 1.1 and 1.2 are now marked as deprecated.
* Swagger version 1.1 is deprecated.
* The requirement to run update-apimanager.py has been removed from the Upgrade steps
## Version [7.7.20200730](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200730_apimgr_relnotes/) {#7.7.20200730}
### Highlights
* 45 issues fixed
### Important changes
* ICAP filter improvements
* Improved upgrade instructions
* MSSQL Database Support
### Deprecated features
* None	
## Version [7.7.20200530](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200530_apimgr_relnotes/) {#7.7.20200530}
### Highlights
* Updated OS Support
* Improved upgrade experience
* 48 issues fixed
### Important changes
* Log4j file format changed to YAML
* Swagger parser libs updated
### Deprecated features
* None
## Version [7.7.20200330](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200330_apimgr_relnotes/) {#7.7.20200330}
### Highlights
* Added TLS 1.3 support
* 25 issues fixed"
### Important changes
* OpenSSL updated to v1.1.1
### Deprecated features
* FIPS support was removed
* The following embedded antivirus scanners will be removed: McAfee, Sophos and Clam AV
## Version [7.7.20200130](https://axway-open-docs.netlify.app/docs/apim_relnotes/20200130_apimgr_relnotes/) {#7.7.20200130}
### Highlights
* Swagger 2.0 enhancements
* Open API Specification (OAS) 3.0 enhancements
* Try it improvements
* Usage tracking improvements
* Back-end API improvements
* API documentation enhancements
* Multi organization beta
* 5 issues fixed
### Important changes
* Increased validation of WSDLs
* Filebeat updated to v6.2.2
* Increased validation of /users endpoint
* Undesirable cipher suites disabled bu default when using SSL/TLS
* Endpoint identification algorithms for LDAPS enabled by default
* Fields that contain confidential information are no longer returned in some API calls
### Deprecated features
* API Tester was removed from instalation
* RAML support was removed
* Export of back-end APIs is not supported for OAS3 or WSDL APIs
* Documentation is no longer provided in PDF format
## Version [7.7 SP2](https://delivery.axway.int/GUI/file/GUI_file_readme.php?3i3aljnfkbsu3pn69e0s7ga307&fileId=74993&readmeId=38812&pdtId=394) {#7.7SP2}
### Highlights
* 64 issues fixed
### Important changes
* Fixed Issue: openid is always accepted as a valid scope in all OAuth configurations.
* Fixed Issue: The response to a HTTP OPTIONS request contains the HTTP OPTIONS request headers.
* Fixed Issue: A malicious user can use a bad scope to force the authentication request to redirect an error message to a non validated URI.
* OpenSSL updated to 1.0.2t-fips to fix security vulnerabilities.
### Deprecated features
* None
## Version [7.7 SP1](https://delivery.axway.int/GUI/file/GUI_file_readme.php?3i3aljnfkbsu3pn69e0s7ga307&fileId=73780&readmeId=38290&pdtId=394) {#7.7SP1}
### Highlights
* 64 issues fixed
### Important changes
* Fixed Issue: Malicious user can overwrite the OAuth scopes passing extra scopes as a form param.
* Fixed Issue: API Manager OAuth implementation allows different client ids in header and body with the possibility of the wrong one being used.
### Deprecated features
* None
## Version [7.7](https://axway-open-docs.netlify.app/docs/apim_relnotes/201904_release/) {#7.7}
### Highlights
* Subscription licensing for API Management
* 5 issues fixed"
### Important changes
* Traffic monitor enhancements
* Configure nested paths in API Gateway Manager
* Filter JMS transactions by custom property in Traffic Monitor
* Redaction support for API Gateway trace log
* Entity Explorer added to API Gateway client tools installer
* Policy Studio filter enhancements
* Elastic topology container deployment enhancements
### Deprecated features
* Support for MySQL Server 2005 has been removed
## Version [7.6.2 SP5](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=76798&readmeId=39732&pdtId=394) {#7.6.2SP5}
### Highlights
* 82 issues fixed
### Important changes
* The jre directory in Policy Studio/Configuration Studio must be remove before applying the Service Pack
### Deprecated features
* None
## Version [7.6.2 SP4](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=73574&readmeId=38165&pdtId=394) {#7.6.2SP4}
### Highlights
* 35 issues fixed
### Important changes
* Fixed Issue: Missing user name validation in API Manager when changing user name of currently logged in user.
* JQuery upadated to 3.4.0 to fix security vulnerabilities.
* Fixed Issue: Security headers are missing from responses.
### Deprecated features
* None
## Version [7.6.2 SP3](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=72882&readmeId=37699&pdtId=394) {#7.6.2SP3}
### Highlights
* 77 issues fixed
### Important changes
* Added CSRF token protection for API Gateway Management APIs.
* Threatening Content filter now scans every query string parameter value regardless of name.
* Input validation for phone and mobile fields and improved email validation have been added.
* jQuery updated to 3.3.1 to fix security vulnerabilities.
* API Gateway checks that authorization code corresponds to client requesting the authorization token and rejects token creation if it does not.
* JRE updated to 1.8.0_202 to fix secu*rity vulnerabilities.
### Deprecated features
* None
## Version [7.6.2 SP2](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=71828&readmeId=37215&pdtId=394) {#7.6.2SP2}
### Highlights
* 20 issues fixed
### Important changes
* Fixed Issue: Security issue allowed upload of unsupported image formats (such as Flash) that could be used to initiate attacks.
* Fixed Issue: Location header in 303 See Other response displayed absolute URIs to host specified in Host header, which could be modified and cause a security issue.
* Fixed Issue: API Gateway SOAP response to a message with an empty body contained a fault namespace indicating that it is an Axway API Gateway.
### Deprecated features
* None
## Version [7.6.2 SP1](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=71453&readmeId=36940&pdtId=394) {#7.6.2SP1}
### Highlights
* 60 issues fixed
### Important changes
* Spring framework updated to 4.3.18.RELEASE to fix security vulnerabilities.
* When authenticated, you can only manage the applications which you are authorized to access.
* Fixed Issue: API Gateway does not fail the decryption of a PGP-encrypted signed message when the Verify option is selected in the filter.
* The Username field validates against a whitelist of allowed characters. Special characters are correctly escaped within emails.
* Fixed Issue: API Gateway Manager UI allowed non logged user to access source files.
* Fixed Issue: You could grant a role access to a higher level than your own using a PUT request.
* OpenSSL updated to 1.0.2p-fips to fix security vulnerabilities.
* Fixed Issue: API Manager users could embed malicious code in client OAuth redirect URLs.
* Bouncy Castle library updated to 1.60 to fix security vulnerabilities.
### Deprecated features
* None
## Version [7.6.2](https://docs.axway.com/bundle/APIGateway_762_ReleaseNotes_allOS_en_HTML5/page/Content/ReleaseNotesPortal/APIGateway_ReleaseNotes_allOS_en.htm) {#7.6.2}
### Highlights
* Elastic topology container deployment
* Smooth rate limiting
### Important changes
* Daily rollover and purging of traffic monitoring data
* Support for /tmp directory mounted with noexec
* Visual Mapper support for multiple schema inputs
* kpsadmin diagnostics
* OAuth configuration in Policy Studio
* Improved threat reporting
* Policy Studio filter enhancements
* Apache Cassandra has been upgraded to version 2.2.12
### Deprecated features
* Axway physical appliance deployment option was removed.
* API Gateway Server support for Windows servers was removed.
* The ConnectToUrlFilter.removePreviousConnections system property is no longer available.
## Version [7.5.3 SP13](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=76137&readmeId=39449&pdtId=394) {#7.5.3SP13}
### Highlights
* 49 issues fixed
### Important changes
* Dojo updated to 1.10.10 to fix security vulnerability
* Fixed Issue: A malicious user can use a bad scope to force the authentication request to redirect the error message to an non validated URI.
* API Gateway now conforms to RFC 7230 and empty headers are left unchanged.
* Fixed Issue: Proxy authorization appears in product traces
### Deprecated features
* None
## Version [7.5.3 SP12](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=74514&readmeId=38555&pdtId=394) {#7.5.3SP12}
### Highlights
* Improvements in the XML redaction
* 35 issues fixed
### Important changes
* Fixed Issue: openid is always accepted as a valid scope in all OAuth configurations.
* Fixed Issue: The response to a HTTP OPTIONS request contains the HTTP OPTIONS request headers.
* Jackson-databind updated to 2.9.10 to fix security vulnerabilities.
### Deprecated features
None
## Version [7.5.3 SP11](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=73425&readmeId=38063&pdtId=394) {#7.5.3SP11}
### Highlights
* The Gateway now includes Zulu OpenJDK 1.8 JRE instead of Oracle JRE 1.8
* It is possible to allow inbound API requests with trailing slash to match an API path with no trailing slash.
* An API method's Content-Type is now checked against the API method's defined MIME type when performing path matching.
* The X-Content-Type-Options HTTP header with value nosniff is not included in a HTTP response serving static content from the API Gateway/API Manager. 
* 42 issues fixed
### Important changes
* Updated cache headers so that user information will not be leaked.
* API Manager applies countermeasures against Timing Attack for API traffic.
* The API Manager Users API /forgotpassword method response no longer shows the distinction between valid and invalid emails. 
* Fixed Issue: Security vulnerability present by not checking the filename parameter for downloading original API file.
* OpenSSL updated to 1.0.2r-fips.
* API Gateway rejects the request if it finds that an extra scope is present as a FormParam.
* Added CSRF token protection for API Gateway Management APIs.
* JQuery updated to 3.4.0
### Deprecated features
*To allow legacy API method matching excluding the method's defined MIME type, the Java property com.coreapireg.apimethod.contenttype.legacy must be set to true
## Version [7.5.3 SP10](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=72293&readmeId=37499&pdtId=394) {#7.5.3SP10}
### Highlights
* 44 issues fixed
### Important changes
* Jython updated to  2.7.1 to fix this security vulnerability.
* jQuery updated to 3.3.1 to fix this security vulnerability.
* JRE updated to 1.8.0_202 to fix this security vulnerability.
* Threatening Content filter now scans every query string parameter value regardless of name.
* JWT token payload is now redacted from tracing at all levels.
* Input validation for phone and mobile fields and improved email validation have been added in the API Manager User API.
* Fixed Issue: Error handling exposed information in API Manager if you issued a PUT request with invalid data in the request body to the advisorybanner API.
* API Gateway now checks that OAuth authorization code corresponds to client requesting the authorization token and rejects token creation if it does not.
### Deprecated features
*Internet Explorer versions 8.0 and 9.0 are no longer officially supported by API Gateway
## Version [7.5.3 SP9](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=71603&readmeId=37068&pdtId=394) {#7.5.3SP9}
### Highlights
* 49 issues fixed
### Important changes
* IBM MQ updated to 7.5.0.8 to fix this security vulnerability.
* OpenSSL updated to 1.0.2p-fips to fix this security vulnerability.
* JRE updated to 1.8.0_191-b12 to fix this security vulnerability.
* apimanager-promote script now requires decryption password or passfile.
* Fixed Issue: Privilege escalation vulnerability, where an API Manager user could give themselves an elevated role using a PUT request.
* Fixed Issue: The URL input field on Add Certificate page can be exploited to check for the existence of files on the server, or to map open ports on local network of API Gateway.
* Fixed Issue: Security vulnerability when entering a file name for export of application where response headers could be changed by entering special characters.
* Fixed Issue: Security vulnerability issue in image upload feature allows not supported image format upload (for example, Flash) which can be used to initiate attacks.
* Fixed Issue: API Manager users could embed malicious code in client OAuth redirect URLs.
* Fixed Issue: URL with ""many slashes"" causes crash in API Gateway.
* Fixed Issue: Path traversal security vulnerability in API Gateway Manager.
* CSRF protection has been added to API Manager Management APIs.
### Deprecated features
* None
## Version [7.5.3 SP8](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=70731&readmeId=36410&pdtId=394) {#7.5.3SP8}
### Highlights
* 19 issues fixed
### Important changes
* Bouncy Castle library updated to 1.60 to fix this security vulnerability.
* Spring framework updated to 4.3.17.RELEASE to fix this security vulnerability.
* JRE updated to 8u181 to fix this security vulnerability.
### Deprecated features
* None
## Version [7.5.3 SP7](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=69650&readmeId=35691&pdtId=394) {#7.5.3SP7}
### Highlights
* 29 issues fixed
### Important changes
* Jackson-databind updated to 2.9.5 to fix this security vulnerability.
* JRE updated to 8u172 to fix this security vulnerability.
* OpenSSL updated to 1.0.2o to fix this security vulnerability.
### Deprecated features
* None
## Version [7.5.3 SP6](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=68637&readmeId=35129&pdtId=394) {#7.5.3SP6}
### Highlights
* 29 issues fixed
### Important changes
* OpenSSL updated to v1.0.2.n to fix security vulnerability.
* Apache Log4j updated to 2.8.2 to fix security vulnerability
* Previously, you could export API collections from API Manager as a plaintext file. Now the generated file is encrypted.
### Deprecated features
* None
## Version [7.5.3 SP5](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=68215&readmeId=34904&pdtId=394) {#7.5.3SP5}
### Highlights
* 32 issues fixed
### Important changes
* OpenSSL updated to 1.0.2m-fips to fix security vulnerability.
* JQuery updated to 2.2.4, to fix security vulnerability.
* commons-email updated to 1.5 to fix security vulnerability
### Deprecated features
* None
## Version [7.5.3 SP4](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=67207&readmeId=34311&pdtId=394) {#7.5.3SP4}
### Highlights
* 12 issues fixed
### Important changes
* Nimbus JOSE+JWT library updated to v4.41.2 to fix security vulnerability
* JRE version updated to v1.8u152 to fix security vulnerability
### Deprecated features
* None
## Version [7.5.3 SP3](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=66867&readmeId=34191&pdtId=394) {#7.5.3SP3}
### Highlights
* 23 issues fixed
### Important changes
* Fixed user sessions in API Manager.
### Deprecated features
* None
## Version [7.5.3](https://docs.axway.com/bundle/APIGateway_753_ReleaseNotes_allOS_en_HTML5/page/Content/ReleaseNotesPortal/APIGateway_ReleaseNotes_allOS_en.htm) {#7.5.3}
### Highlights
* 68 issues fixed
### Important changes
* Apache ActiveMQ updated to 5.14.3 to fix security vulnerabilities.
* JSCH update to 0.1.54 to fix security vulnerabilities.
* owasp esapi updated to 2.1.0.1 to fix security vulnerabilities.
* JRE updated to 8u121 to fix security vulnerabilities.
* xmlsec updated to 1.5.8 to fix security vulnerabilities.
* spring-core updated to v4.3.5 to fix security vulnerabilities.
* Jsch dependency updated v0.1.54  to fix security vulnerabilities.
* Remove Fluent-hc dependency from API Gateway.
* The SSL compression now is disabled by default.
### Deprecated features
* Sun Access Manager filters have been deprecated and will be removed in a future release.
* API Gateway Analytics is deprecated and will be removed in a future release.
* The OpenID connect filters in Policy Studio have been deprecated and will be removed in a future release
* Support for Tivoli Access Manager version 6.0 has been removed and replaced by support for Tivoli Access Manager version version 6.1.
* The ISO format for API Gateway virtual appliance has been replaced by the OVA format.
* The jabber and restJabber code samples are no longer included in the INSTALL_DIR/apigateway/samples/developer_guide directory and are no longer available for download from Axway Support"
## Version [7.5.3 SP2](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=66298&readmeId=33893&pdtId=394) {#7.5.3SP2}
### Highlights
* 12 issues fixed
### Important changes
* JSCH update to 0.1.54 to fix security vulnerabilities.
### Deprecated features
* None
## Version [7.5.3 SP1](https://delivery.axway.int/GUI/file/GUI_file_readme.php?p93l6105cr4j87nrgp10c4jqj7&fileId=65525&readmeId=33421&pdtId=394) {#7.5.3SP1}
### Highlights
* 24 issues fixed
### Important changes
* JRE updated to v8u131 to fix security vulnerability.
* Fixed Issue: The Revoke OAuth Token filter does not revoke a refresh token if the access token has already expired.
### Deprecated features
* None
