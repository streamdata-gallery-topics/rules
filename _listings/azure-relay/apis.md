---
name: Azure Relay
description: The Azure Relay service facilitates hybrid applications by enabling you
  to securely expose services that reside within a corporate enterprise network to
  the public cloud, without having to open a firewall connection, or require intrusive
  changes to a corporate network infrastructure. Relay supports a variety of different
  transport protocols and web services standards.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Relay
- Proxy
- Microsoft
created: "2018-03-24"
modified: "2018-03-24"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-relay/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure Relay API
  description: The Azure Relay service facilitates hybrid applications by enabling
    you to securely expose services that reside within a corporate enterprise network
    to the public cloud, without having to open a firewall connection, or require
    intrusive changes to a corporate network infrastructure
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-relay/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-relay-namespaces-namespacename-wcfrelays-relayname-authorizationrules-get.md
- name: Azure Relay API WCFRelays List Authorization Rules
  description: Authorization rules for a WCFRelays.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/service-relay-bus.png
  humanURL: ""
  baseURL: http:://management.azure.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-relay/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-relay-namespaces-namespacename-wcfrelays-relayname-authorizationrules-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-relay/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-relay-namespaces-namespacename-wcfrelays-relayname-authorizationrules-get-postman.md
x-common:
- type: x-blog
  url: https://blogs.msdn.microsoft.com/servicebus/
- type: x-blog-rss
  url: https://blogs.msdn.microsoft.com/servicebus/feed/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-bus-relay/
- type: x-pricing
  url: https://azure.microsoft.com/pricing/details/service-bus/
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/azure-servicebusrelay
- type: x-blog
  url: https://blogs.msdn.microsoft.com/servicebus/
- type: x-blog-rss
  url: https://blogs.msdn.microsoft.com/servicebus/feed/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-bus-relay/
- type: x-pricing
  url: https://azure.microsoft.com/pricing/details/service-bus/
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/azure-servicebusrelay
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---