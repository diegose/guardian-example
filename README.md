# Guardian example
Example for Guardian configuration and transaction API

## Setup
You need to setup the following variable on your server in order for this example to work
```
AUTH0_API_TOKEN: 'See https://auth.com/docs/api/management/v2',
AUTH0_DOMAIN: '{tenant}.auth0.com',
AUTH0_SECRET: 'Client secret: DON\'T NOT COMMIT TO GIT REPO',
AUTH0_CLIENT: 'Client id',
AUTH0_TENANT: 'Name of your tenant',
AUTH0_REGION: 'au|us|eu',
COOKIE_SECRET: 'Secret to sign generated cookies DON\'T NOT COMMIT TO GIT REPO',
MY_API_SECRET: 'Secret to sign your own tokens DON\'T NOT COMMIT TO GIT REPO'
```

## User profile
![User profile](https://github.com/auth0/guardian-example/raw/master/readme.d/user.png)

## MFA Configuration
![MFA Configuration](https://github.com/auth0/guardian-example/raw/master/readme.d/mfa-configuration.png)

## Step up / Require login
![Step up](https://github.com/auth0/guardian-example/raw/master/readme.d/step-up.png)
