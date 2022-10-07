# Readings 15

## what is OAuth

1. OAuth is an authorization protocol that describes how a service and a server can provide authorization to their site

2. Using OAuth is like when you click sign in with google on a non google site
3. OAuth only works using Http requests and follows these steps:
    - The first website connects to the second on behalf of the user
    - The second site generates a one time token
    - The first site gives this to the users software
    - The client software gives this to their authentication provider
    - If the client hasn’t already authenticated the provider will ask for authorization, then the client asks to authorize the transaction to the second site.
    - the users approves a particular transaction type to the first website
    - the user then is given an approved access token
    - the user gives the token to the first site
    - the first gives their token to the second
    - the second site gives access to the first on behalf of the user
    - the user sees a successful transaction occur
4. OpenID is an authentication protocol used for humans to connect with machines where as OAuth is for machines connecting to machines on behalf of humans.

## Authentication and Authorization Flows

1. What is the difference between authorization and authentication?
    - authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.
2. What is Authorization Code Flow?
    - code grant type that is used to obtain both access tokens and refresh tokens and is optimized for confidential clients.
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
    - This is an additional level of security implemented for gaining access to secure information. PKCE introduces a secret created by the calling application that can be verified by the authorization server.
4. What is Implicit Flow with Form Post?
    - An alternative to Authorization Code Flow, that provides the implicit flow, which is intended for public clients, or applications which are unable to securely store client secrets. (not best practice)
5. What is Client Credentials Flow?
    - With M2M apps, Client Credentials Flow authenticates and authorizes the app, rather than the user.
6. What is Device Authorization Flow?
    - Rather than authenticate the user directly, input constrained devices via the internet can ask the user to go to a link on their computer or phone and authorize the device. (Multi authenticators!)
7. What is Resource Owner Password Flow?
    - Highly trusted apps can use this flow to request that users provide credentials via an interactive form. (remember my password…)(Not to be used by third party clients as it involves handling the user’s password)
