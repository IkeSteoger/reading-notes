# 301 Reading 15

## Authentication

>What is OAuth?
>>It is an open-standard authorization protocol or framework that describes how unrelated servers & services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. (csoonline.com)

>Give an example of what using OAuth would look like.
>>Simplest example is when you go to log onto a website and it offers one or more opportunitues to log on using another website/service logon (aka gmail)

>How does OAuth work? What are the steps that it takes to authenticate the user?
>>OAuth works like a valet key - it allows you access to drive the car but doesn't allow full access to all the bells and whistles. 
>> "The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved. The first site gives this token and secret to the initiating user’s client software.
The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
The user approves (or their software silently approves) a particular transaction type at the first website.
The user is given an approved access token (notice it’s no longer a request token).
The user gives the approved access token to the first website.
The first website gives the access token to the second website as proof of authentication on behalf of the user.
The second website lets the first website access their site on behalf of the user.
The user sees a successfully completed transaction occurring.
OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons)." - csoonline.com


>What is OpenID?
>>OpenID is about authentication "OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans." (StackOverflow)

>What is the difference between authorization and authentication?
>>Authentication verifies the identity of a user or service, and authorization determines their access rights.

>What is Authorization Code Flow?
>>Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization Code for a token. (auth0.com)

>What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
>>During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE). (auth0.com)

>What is Implicit Flow with Form Post?
>>As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets. While this is no longer considered a best practice for requesting Access Tokens, when used with Form Post response mode, it does offer a streamlined workflow if the application needs only an ID token to perform user authentication. (auth0.com)

>What is Client Credentials Flow?
>>With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4). (auth0.com)

>What is Device Authorization Flow?
>>With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text. To do this, device apps use the Device Authorization Flow (drafted in OAuth 2.0). For use with mobile/native applications. (auth0.com)

>What is Resource Owner Password Flow?
>>Though we do not recommend it, highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used. (auth0.com)
