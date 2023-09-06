## What is OAuth?

OAuth is like a digital key that lets you use one website's login to access another website without having to create a new password.

## Give an example of what using OAuth would look like.

It is like going to a new website and instead of creating a new account, you just click a "Sign in with Facebook" button.

## How does OAuth work? What are the steps that it takes to authenticate the user?

When you use OAuth, the website you're trying to access asks another website (like Facebook or Google) if it knows you. If you're logged in there and give permission, the first website gets a confirmation to let you in without needing a new password.

## What is OpenID?

OpenID is another way to sign in to websites using one account, like using your Gmail address to sign into other websites.

## What is the difference between authorization and authentication?

*Authentication* verifies a user's identity, *authorization* determines their permissions.

## What is Authorization Code Flow?

It's a method where web apps exchange an Authorization Code for a token, keeping the code's source private.

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

It's a secure version of Authorization Code Flow, designed for mobile and single-page apps using a special proof key.

## What is Implicit Flow with Form Post?

It's an OAuth 2.0 method for public clients to get an ID token directly without fetching access tokens.

## What is Client Credentials Flow?

It's a method for machine-to-machine apps where the system grants access based on the app's credentials, not a user's.

## What is Device Authorization Flow?

It's for devices with limited input, prompting users to authorize them via a link on another device.

## What is Resource Owner Password Flow?

It's a flow for trusted apps where users directly provide their credentials. It is often used when other methods aren't able to use.

## Reference Links

- [What is OAuth](https://www.csoonline.com/article/562635/what-is-oauth-how-the-open-authorization-framework-works.html)

- [Authorization and Authentication flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)
