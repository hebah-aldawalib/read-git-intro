# What is OAuth ?

*What is OAuth?*
 is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password.

 *Give an example of what using OAuth would look like.*

 acebook, GitHub

 *How does OAuth work? What are the steps that it takes to authenticate the user?*

 There are 3 main players in an OAuth transaction: the user, the consumer, and the service provider

 Step 1 – The User Shows Intent

- Joe (User): “Hey, Bitly, I would like you to be able to post links directly to my Twitter stream.”
- Bitly (Consumer): “Great! Let me go ask for permission.”

Step 2 – The Consumer Gets Permission

- Bitly: “I have a user that would like me to post to his stream. Can I have a request token?”
Twitter (Service Provider): “Sure.  Here’s a token and a secret.”


*What is OpenID?*

OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords.


# Authorization and Authentication flows


*What is the difference between authorization and authentication?*

 Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.

 *What is Authorization Code Flow?*

 is used to obtain an access token to authorize API requests. ... Access tokens while having a limited lifetime, can be renewed with a refresh token

 *What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?*

The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange

*What is Implicit Flow with Form Post?*

Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls

*What is Client Credentials Flow?*

The Client Credentials flow is a server to server flow. There is no user authentication involved in the process. ... This flow is useful for systems that need to perform API operations when no user is present. It can be nightly operations, or other that involve contacting OAuth protected APIs.

*What is Device Authorization Flow?*

The authorization flow defined by this specification, sometimes referred to as the "device flow", instructs the user to review the authorization request on a secondary device, such as a smartphone, which does have the requisite input and browser capabilities to complete the user interaction.

*What is Resource Owner Password Flow?*

The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token. This flow has significantly different security properties than the other OAuth flows. The primary difference is that the user’s password is accessible to the application. This requires strong trust of the application by the user.