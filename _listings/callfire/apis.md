---
name: CallFire
x-slug: callfire
description: Grow your business with virtual phone numbers, IVR, voice broadcasting,
  mass text messaging services and power dialing. Try CallFire for FREE!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
x-kinRank: "9"
x-alexaRank: "129466"
tags: Numbers
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/apis.md
specificationVersion: "0.14"
apis:
- name: CallFire - Find leases
  x-api-slug: numbersleases-get
  description: Searches for all numbers leased by account user. This API is useful
    for finding all numbers currently owned by the user. Returns a paged list of number
    leases.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleases-get-openapi.md
- name: CallFire - Find lease configs
  x-api-slug: numbersleasesconfigs-get
  description: Searches for all number lease configs for the user. Returns a paged
    list of NumberConfig
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigs-get-openapi.md
- name: CallFire - Find a specific lease config
  x-api-slug: numbersleasesconfigsnumber-get
  description: Returns a single NumberConfig instance for a given number lease
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigsnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigsnumber-get-openapi.md
- name: CallFire - Update a lease config
  x-api-slug: numbersleasesconfigsnumber-put
  description: Updates a phone number lease configuration. Use this API endpoint to
    add an Inbound IVR or Call Tracking feature to a CallFire phone number. Call tracking
    configuration allows you to track the incoming calls, to analyze and to respond
    customers using sms or voice replies. For more information see [call tracking
    page](https://www.callfire.com/products/call-tracking)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigsnumber-put-openapi.md
- name: CallFire - Find a specific lease
  x-api-slug: numbersleasesnumber-get
  description: Returns a single NumberLease instance for a given number
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesnumber-get-openapi.md
- name: CallFire - Update a lease
  x-api-slug: numbersleasesnumber-put
  description: Updates a number lease instance. Ability to turn on/off autoRenew and
    toggle call/text features for a particular number
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesnumber-put-openapi.md
- name: CallFire - Find local numbers
  x-api-slug: numberslocal-get
  description: Searches for numbers available for purchase in CallFire local numbers
    catalog . At least one additional parameter is required. User may filter local
    numbers by their region information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numberslocal-get-openapi.md
- name: CallFire - Find number regions
  x-api-slug: numbersregions-get
  description: Searches for region information. Use this API to obtain detailed region
    information that can be used to query for more specific phone numbers than a general
    query.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersregions-get-openapi.md
- name: CallFire - Find tollfree numbers
  x-api-slug: numberstollfree-get
  description: Searches for the toll free numbers which are available for purchase
    in the CallFire catalog
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numberstollfree-get-openapi.md
- name: CallFire - Purchase numbers
  x-api-slug: ordersnumbers-post
  description: Purchase numbers. There are many ways to purchase a number. Set either
    'tollFreeCount' or 'localCount' along with some querying fields to purchase numbers
    by bulk query. Set the list of numbers to purchase by list. Available numbers
    will be purchased using CallFire credits owned by the user. Make sure the account
    has enough credits before trying to purchase
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/ordersnumbers-post-openapi.md
- name: CallFire - Delete do not contact (dnc) number. If number contains commas treat
    as list of numbers
  x-api-slug: contactsdncsnumber-delete
  description: Delete a Do Not Contact (DNC) contact entry.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/contactsdncsnumber-delete-openapi.md
- name: CallFire - Get do not contact (dnc)
  x-api-slug: contactsdncsnumber-get
  description: Get Do Not Contact (DNC) object create by user. This DoNotContact entry
    only affects calls/texts/campaigns on this account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/contactsdncsnumber-get-openapi.md
- name: CallFire - Update an individual do not contact (dnc) number
  x-api-slug: contactsdncsnumber-put
  description: Update a Do Not Contact (DNC) contact entry. Can toggle whether the
    DNC is enabled for calls/texts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/contactsdncsnumber-put-openapi.md
- name: CallFire - Find a specific lease config
  x-api-slug: numbersleasesconfigsnumber-get
  description: Returns a single NumberConfig instance for a given number lease
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigsnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigsnumber-get-openapi.md
- name: CallFire - Update a lease config
  x-api-slug: numbersleasesconfigsnumber-put
  description: Updates a phone number lease configuration. Use this API endpoint to
    add an Inbound IVR or Call Tracking feature to a CallFire phone number. Call tracking
    configuration allows you to track the incoming calls, to analyze and to respond
    customers using sms or voice replies. For more information see [call tracking
    page](https://www.callfire.com/products/call-tracking)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigsnumber-put-openapi.md
- name: CallFire - Find a specific lease
  x-api-slug: numbersleasesnumber-get
  description: Returns a single NumberLease instance for a given number
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesnumber-get-openapi.md
- name: CallFire - Update a lease
  x-api-slug: numbersleasesnumber-put
  description: Updates a number lease instance. Ability to turn on/off autoRenew and
    toggle call/text features for a particular number
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesnumber-put-openapi.md
- name: CallFire - Update a lease
  x-api-slug: numbersleasesnumber-put
  description: Updates a number lease instance. Ability to turn on/off autoRenew and
    toggle call/text features for a particular number
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesnumber-put-openapi.md
- name: CallFire - Find a specific lease
  x-api-slug: numbersleasesnumber-get
  description: Returns a single NumberLease instance for a given number
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesnumber-get-openapi.md
- name: CallFire - Update a lease config
  x-api-slug: numbersleasesconfigsnumber-put
  description: Updates a phone number lease configuration. Use this API endpoint to
    add an Inbound IVR or Call Tracking feature to a CallFire phone number. Call tracking
    configuration allows you to track the incoming calls, to analyze and to respond
    customers using sms or voice replies. For more information see [call tracking
    page](https://www.callfire.com/products/call-tracking)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigsnumber-put-openapi.md
- name: CallFire - Find a specific lease config
  x-api-slug: numbersleasesconfigsnumber-get
  description: Returns a single NumberConfig instance for a given number lease
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigsnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/numbersleasesconfigsnumber-get-openapi.md
- name: CallFire - Update an individual do not contact (dnc) number
  x-api-slug: contactsdncsnumber-put
  description: Update a Do Not Contact (DNC) contact entry. Can toggle whether the
    DNC is enabled for calls/texts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/contactsdncsnumber-put-openapi.md
- name: CallFire - Get do not contact (dnc)
  x-api-slug: contactsdncsnumber-get
  description: Get Do Not Contact (DNC) object create by user. This DoNotContact entry
    only affects calls/texts/campaigns on this account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/contactsdncsnumber-get-openapi.md
- name: CallFire - Delete do not contact (dnc) number. If number contains commas treat
    as list of numbers
  x-api-slug: contactsdncsnumber-delete
  description: Delete a Do Not Contact (DNC) contact entry.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/numbers/master/_listings/callfire/contactsdncsnumber-delete-openapi.md
x-common:
- type: x--net-sdk
  url: https://github.com/CallFire/CallFire-CSharp-SDK
- type: x-account-billing
  url: https://answers.callfire.com/hc/en-us/sections/200166268-Billing
- type: x-account-settings
  url: https://answers.callfire.com/hc/en-us/sections/200187056-Account-Settings
- type: x-api-gallery
  url: http://bureau.of.justice.statistics.api.gallery.streamdata.io
- type: x-api-stack
  url: http://callfire.stack.network
- type: x-authentication
  url: https://www.callfire.com/api-documentation/how-do-i-enable-api-on-my-account
- type: x-blog
  url: https://www.callfire.com/blog
- type: x-blog-rss
  url: https://www.callfire.com/blog/feed
- type: x-twitter
  url: https://twitter.com/CallFire
- type: x-case-studies
  url: https://www.callfire.com/case-studies
- type: x-compliance
  url: https://www.callfire.com/legal/compliance
- type: x-contact-form
  url: https://www.callfire.com/contact
- type: x-crunchbase
  url: https://www.crunchbase.com/organization/callfire
- type: x-crunchbase
  url: https://crunchbase.com/organization/callfire
- type: x-developer
  url: https://www.callfire.com/api-documentation
- type: x-documentation
  url: https://www.callfire.com/api-documentation/rest/version/1.1
- type: x-drupal-plugin
  url: https://github.com/CallFire/CallFire-Drupal-Integration
- type: x-email
  url: answers@callfire.com
- type: x-email
  url: support@callfire.com
- type: x-facebook
  url: https://www.facebook.com/callfire
- type: x-faq
  url: https://answers.callfire.com/hc/en-us/sections/200193833-FAQs
- type: x-getting-started
  url: https://www.callfire.com/help/docs/getting-started
- type: x-github
  url: https://github.com/callfire
- type: x-glossary
  url: https://www.callfire.com/help/glossary/communications
- type: x-google-plus
  url: https://plus.google.com/100142045997033051154
- type: x-messages
  url: https://www.callfire.com/ui/number/messages?6
- type: x-partners
  url: https://www.callfire.com/partners
- type: x-phone
  url: 1.877.897.3473
- type: x-php-sdk
  url: https://github.com/CallFire/CallFire-PHP-SDK
- type: x-pricing
  url: https://www.callfire.com/pricing
- type: x-privacy
  url: https://www.callfire.com/legal/privacy
- type: x-selfservice-registration
  url: https://www.callfire.com/ui/register?1
- type: x-terms-of-service
  url: https://www.callfire.com/legal/terms
- type: x-tickets
  url: https://answers.callfire.com/hc/en-us/requests/new
- type: x-tour
  url: javascript:;
- type: x-videos
  url: https://answers.callfire.com/hc/en-us/articles/200849247-Videos
- type: x-webinars
  url: https://answers.callfire.com/hc/en-us/articles/202174798-Webinars
- type: x-website
  url: http://www.callfire.com
- type: x-wordpress-plugin
  url: https://github.com/CallFire/CallFire-WordPress-Integration
- type: x-youtube
  url: https://www.youtube.com/user/CallFireTelephony
- type: x-zapier
  url: https://zapier.com/zapbook/callfire/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---