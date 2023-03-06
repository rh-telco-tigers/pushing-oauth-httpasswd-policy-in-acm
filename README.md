In this article, I am going to show a practical example of pushing a policy in ACM.  Many customers ask for a way to control the authentication provider(s) that are supported by OCP.  In this example, an htpasswd oauth provider will be created as well as a central secret (for those password credentials).  This same method can be used to push an LDAP/Active Directory mechanism as well.

A sample Git repo is located at https://github.com/kcalliga/acm-demos/blob/master/oauth-policy

The related article is located at https://www.myopenshiftblog.com/pushing-an-authentication-policy-in-advanced/
