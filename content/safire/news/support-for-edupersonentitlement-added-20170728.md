---
date: 2017-07-28 10:53:04+00:00
slug: support-for-edupersonentitlement-added-20170728
tags:
  - attributes
  - eduPersonEntitlement
  - library
  - technical
title: Support for eduPersonEntitlement added
url: /safire/news/support-for-edupersonentitlement-added-20170728/
---

In our ongoing work to [integrate library journal and platform providers]({{< ref "/technical/resources/library-services.md" >}}), it has become apparent that we need to support the [eduPersonEntitlement]({{< ref "/technical/attributes/edupersonentitlement.md" >}}) attribute. Support for this attribute has therefore been added to the Federation hub, as well as the test identity and service providers.

To ease transition and to lower barriers to entry, the Federation hub may automatically generate a value for _eduPersonEntitlement_ from [eduPersonAffilation]({{< ref "/technical/attributes/edupersonaffiliation.md" >}}) if none is supplied by the identity provider. Details of this are in the [attribute definition]({{< ref "/technical/attributes/edupersonentitlement.md" >}}). (You can avoid having _eduPersonEntitlement_ auto-generated by supplying more accurate value(s).)
