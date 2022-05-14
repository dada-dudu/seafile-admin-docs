# Single Sign-On

Seafile Server Community Edition as well as Seafile Server Professional Edition support single sign-on (SSO) authentication protocols. Seafile Server Professional Edition supports most of the popular protocols.

Both editions also support SSO authentication in the Seafile Add-in for Outlook.

## SSO support in Community Edition

The Community Edition supports the following SSO protocols:

* [Shibboleth](./shibboleth_config_v6.3.md)
* [OAuth](./oauth.md)
* [Remote User (Proxy Server)](./remote_user.md)

Kerberos authentication can be integrated by using Apache as a proxy server. Follow the instructions in [Remote User Authentication](./remote_user.md).

## SSO support in Professional Edition

The Professional Edition supports the following SSO protocols in addition those supported by the Community Edition:

* [ADFS or SAML 2.0](../deploy_pro/adfs.md)
* [CAS](../deploy_pro/cas.md) (deprecated)

## SSO authentication with the Seafile Add-in for Outlook

The Seafile Add-in for Outlook can use the SSO protocol configured on the Seafile Server it connects to, provided some extra configuration has been done.
