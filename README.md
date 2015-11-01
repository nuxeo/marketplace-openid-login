# OpenID Login Nuxeo Package

Nuxeo package for the OpenID authentication plugin that can handle [Amazon login](https://login.amazon.com/), [Github](https://developer.github.com/v3/oauth/), [Google](https://developers.google.com/identity/protocols/OAuth2), [Google+](https://developers.google.com/+/web/api/rest/oauth), [LinkedIn](https://developer.linkedin.com/docs/oauth2) and [Facebook](https://developers.facebook.com/docs/facebook-login).

## Manual Configuration after Package Installation

Please read the [documentation](https://doc.nuxeo.com/x/1BM5AQ) carefully.

After installing the plugin, take a look at the `config/openid-login-config.xml` file in the `openid` template folder to understand how ti works.
You can configure the global template just by setting the following values in `nuxeo.conf` depending of your target provider. You can only set the ones you need.

    # Github
    nuxeo.openid.github.client.id=
    nuxeo.openid.github.client.secret=

    # Google
    nuxeo.openid.google.client.id=
    nuxeo.openid.google.client.secret=

    # Google+
    nuxeo.openid.googleplus.client.id=
    nuxeo.openid.googleplus.client.secret=

    # LinkedIn
    nuxeo.openid.linkedin.client.id=
    nuxeo.openid.linkedin.client.secret=

    # Amazon Connect
    nuxeo.openid.amazon.client.id=
    nuxeo.openid.amazon.client.secret=

    # Facebook Connect
    nuxeo.openid.facebook.client.id=
    nuxeo.openid.facebook.client.secret=


## Building Nuxeo Package

    mvn clean install

# About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris. More information is available at www.nuxeo.com.
