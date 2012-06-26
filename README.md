picketlink-idm-api
==================

PicketLink Identity Model API


Some of the requirements that have been provided by potential consumers of this API are:

1) A typed API to store an Identity, Attributes, Tokens, Certificates and Questions (such as in a banking site), Roles and Groups.
2) The API should be simple.
3) Identity configuration via annotations that can be injected into the API.
4) The Identity Store API can use an LDAP and/or DB. 
  - Data can be loaded into an LDAP using LDIF conforming standard LDAP schema.
  - Data in DB need to be configured in the Identity Configuration (annotations)
  - DB configuration will go into persistence.xml as per JPA spec. 
5) Advanced usages such as a detyped API (involving IdentityObject and IdentityType classes) can be provided if desired. But it has to be separate from the typed API.
