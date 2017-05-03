# Authentication in Golang with JWT

Authenticate a Golang API with JSON Web Tokens (JWT). This repo contains the code samples for the [Authentication in Golang with JWT](https://auth0.com/blog/2016/04/13/authentication-in-golang/) article.

## Setup

1. Update the `main.go` file with your Auth0 Credentials. [Sign up](https://auth0.com) for an account for free if you don't have one.
2. Update the `auth0-variables.js` file in `static/js` with your Auth0 Credentials.
3. Add `http://localhost:3000` to your Allowed Callback, and Allowed Logout URL's in your [Auth0 Management Dashboard](https://manage.auth0.com).
4. Launch the application by running `go run main.go`
5. Navigate to `localhost:3000` to view the application

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, amont others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a free Auth0 account

1. Go to [Auth0](https://auth0.com/signup) and click Sign Up.
2. Use Google, GitHub or Microsoft Account to login.

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
