# spring-petclinic-microservices-config

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Configuration repository for distributed Spring Petclinic application

The feature can be toggled by togglz.
For example, in the customers-service.yml you can edit the CALL_PEOPLE_SERVICE.enabled to false to disable the feature.

togglz:
  features:
    CALL_PEOPLE_SERVICE:
      enabled: true