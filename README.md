# schub-cas

CAS SSO Maven overlay configuration with LDAP and ClearPass

Many features require a functioning and at least locally trusted SSL configuration.

For configuration the following files need to be adjusted:
* /src/main/webapp/WEB-INF/cas.properties
* /src/main/webapp/WEB-INF/deployerConfigContext.xml

Building: Build using Maven with package goal