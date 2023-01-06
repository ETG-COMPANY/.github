# ETG DEV docs

## Development process

### Task management

The development process is based on a Kanban methodology, and planned in a board as follows:

* [Kanban development board (click here)](https://github.com/orgs/ETG-COMPANY/projects/1/views/1)

### Process steps

TBD

## Projects

### AENTE

Web system to manage resources of companies from different business domains. The initial project scope is planned to be used in laboratories, clinics, doctors' offices, hospitals, etc.

#### Repository

[https://github.com/ETG-COMPANY/aente](https://github.com/ETG-COMPANY/aente)

### ETG website

Static pages for the institutional presentation of ETG. Available at [etg.company](https://etg.company)

#### Repository

[https://github.com/ETG-COMPANY/etg-company-website](https://github.com/ETG-COMPANY/etg-company-website)

## DevOps

### CI/CD with Jenkins

#### Access
```
URL: http://208.109.215.200
User: (ask the admin)
Password: (ask the admin)
```

### Testing environment

#### AENTE

```
URL: https://biobots.com.br
User: (ask the admin)
Password: (ask the admin)
```

#### ETG website

This project is tested only in the developer's local and production environments.

#### Jobs

* aente: job to build AENTE project and deploy it in the test environment (code pulled from the `HML` branch)
* etg-website: job to deploy the ETG website project in the production environment (code pulled from the `main` branch)
