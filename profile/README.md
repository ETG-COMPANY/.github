# ETG DEV docs

## Development process

### Process steps

1. Refine task
2. Develop task
3. Test
4. Deploy

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
URL: (ask the admin)
User: (ask the admin)
Password: (ask the admin)
```

### Testing environment

#### AENTE

```
URL: (ask the admin)
User: (ask the admin)
Password: (ask the admin)
```

#### ETG website

This project is tested only in the developer's local and production environments.

#### Jobs

* **aente**: job to build AENTE project and deploy it in the test environment (code pulled from the `HML` branch)
* **etg-website**: job to deploy the ETG website project in the production environment (code pulled from the `main` branch)
