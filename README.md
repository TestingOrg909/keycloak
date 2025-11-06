
# Open Source Identity and Access Management

Add authentication to applications and secure services with minimum effort. No need to deal with storing users or authenticating users.

Keycloak provides user federation, strong authentication, user management, fine-grained authorization, and more.


## Help and Documentation

* [Documentation](https://www.keycloak.org/documentation.html)

## Reporting Security Vulnerabilities

If you have found a security vulnerability, please look at the [instructions on how to properly report it](https://github.com/keycloak/keycloak/security/policy).


## Reporting an issue

If you believe you have discovered a defect in Keycloak, please open [an issue](https://github.com/keycloak/keycloak/issues).
Please remember to provide a good summary, description as well as steps to reproduce the issue.


## Getting started

To run Keycloak, download the distribution from our [website](https://www.keycloak.org/downloads.html). Unzip and run:

    bin/kc.[sh|bat] start-dev

Alternatively, you can use the Docker image by running:

    docker run quay.io/keycloak/keycloak start-dev
    
For more details refer to the [Keycloak Documentation](https://www.keycloak.org/documentation.html).


## Building from Source

To build from source, refer to the [building and working with the code base](docs/building.md) guide.


### Testing

To run tests, refer to the [running tests](docs/tests.md) guide.

## Other Keycloak Projects

* [Keycloak](https://github.com/keycloak/keycloak) - Keycloak Server and Java adapters
* [Keycloak QuickStarts](https://github.com/keycloak/keycloak-quickstarts) - QuickStarts for getting started with Keycloak
* [Keycloak Node.js Connect](https://github.com/keycloak/keycloak-nodejs-connect) - Node.js adapter for Keycloak


## License

* [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)
