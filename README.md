# Welcome

This site contains all documentation for the mFACTA product.

{% embed url="https://mfacta.com" %}

{% hint style="info" %}
Signata MFA/Enterprise was rebranded to mFACTA. Some parts of the product still show the old Signata branding.
{% endhint %}

A presentation discussing the product is here:

{% embed url="https://github.com/cl-tim/signata-mfa-docs/blob/main/signata-mfa-overview-presentation.pdf" %}

You can also access support here:

{% embed url="https://congruentlabs.atlassian.net/servicedesk/customer/portal/2" %}

If you find any problems with this documentation please contact support.

### mFACTA Standalone

mFACTA Standalone Edition is a product that allows the issuance of PKI certificates onto YubiKeys for users within your network. Because mFACTA Standalone leverages existing services within your network, additional steps are required to be completed to ensure your network is ready for integration. The documents in this repository details these steps, and it is recommended that the linked documents below are reviewed before attempting to integrate mFACTA Standalone, as you may be delayed in getting some pre-requisites configured first.

Some of the pre-requisites include:

* Access to an Active Directory Domain Services (ADDS) server that mFACTA can connect to read identity information for your users.
* Access to an Active Directory Certificate Services (ADCS) server that mFACTA can connect to for requesting certificates.
* Modification/Configuration of Certificate Templates for Signata to be able to request certificates for users.
* A server within your network that the mFACTA service can be installed on to, and IIS also enabled for use as a reverse proxy.

These documents aim to provide guidance for configuration of the services in the most simple and optimal manner.

{% content-ref url="standalone-server-installation-guide.md" %}
[standalone-server-installation-guide.md](standalone-server-installation-guide.md)
{% endcontent-ref %}

{% content-ref url="standalone-client-installation-guide.md" %}
[standalone-client-installation-guide.md](standalone-client-installation-guide.md)
{% endcontent-ref %}

{% content-ref url="troubleshooting.md" %}
[troubleshooting.md](troubleshooting.md)
{% endcontent-ref %}
