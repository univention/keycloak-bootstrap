# Keycloak bootstrap

This repository contains a set of scripts to bootstrap a Keycloak server.

Features:

- Login links.
- LDAP mappers.
- Two factor authentication.


## Configuration

### Login links

To customize the login links, set the folowwing value:

```yaml
bootstrap:
 loginLinks:
    - link_number: 1
      description: "Test Link"
      language: "en"
      href: "https://www.univention.de/"
```
