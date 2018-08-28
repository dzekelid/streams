---
name: TradeStation
x-slug: tradestation
description: Whether you trade stocks, ETFs, options or futures, TradeStation???s
  award-winning tools and brokerage services can give you the confidence to achieve
  your goals.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
x-kinRank: "7"
x-alexaRank: "37688"
tags: Streams
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/apis.md
specificationVersion: "0.14"
apis:
- name: Tradestation API - Stream Quote Changes
  x-api-slug: streamquotechangessymbols-get
  description: |-
    Streams the latest Quote information for the given Symbols. The first chunk in the stream is a full quote snapshot - subsequent chunks only contain fields of the quote object that have changed since the last chunk.

    An invalid symbol name will result in a response of this form - {"Symbol":"BADEXAMPLESYMBOL","Error":"FAILED, EX_INVALID_SYMBOL"}

    If the user is not entitled for the symbol requested, response will be of this form - {"Symbol":"EXAMPLESYMBOL","Error":"FAILED, EX_NOT_ENTITLED"}
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotechangessymbols-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotechangessymbols-get-openapi.md
- name: Tradestation API - Stream Quote Snapshots
  x-api-slug: streamquotesnapshotssymbols-get
  description: |-
    Streams the latest Quote for the given Symbols. Each chunk is a full quote object.

    An invalid symbol name will result in a response of this form - {"Symbol":"BADSYMBOLEXAMPLE","Error":"FAILED, EX_INVALID_SYMBOL"}

    If the user is not entitled for the symbol requested, response will be of this form - {"Symbol":"EXAMPLESYMBOL","Error":"FAILED, EX_NOT_ENTITLED"}
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotesnapshotssymbols-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotesnapshotssymbols-get-openapi.md
- name: Tradestation API - Stream BarChart - Starting on Date
  x-api-slug: streambarchartsymbolintervalunitstartdate-get
  description: Streams barchart data starting from startDate, each bar filling quantity
    of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdate-get-openapi.md
- name: Tradestation API - Stream BarChart - Date Range
  x-api-slug: streambarchartsymbolintervalunitstartdateenddate-get
  description: Streams barchart data starting from startDate to end date, each bar
    filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdateenddate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdateenddate-get-openapi.md
- name: Tradestation API - Stream BarChart - Bars Back
  x-api-slug: streambarchartsymbolintervalunitbarsbacklastdate----get
  description: Streams barchart data starting from a number of bars back from last
    date, each bar filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitbarsbacklastdate----get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitbarsbacklastdate----get-openapi.md
- name: Tradestation API - Stream BarChart - Days Back
  x-api-slug: streambarchartsymbolintervalunit-get
  description: Streams barchart data starting from a number of days back from last
    date, each bar filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunit-get-openapi.md
- name: Tradestation API - Stream Tick Bars
  x-api-slug: streamtickbarssymbolintervalbarsback-get
  description: Streams tick bars data from a number of bars back, each bar returned
    separated by interval number of ticks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamtickbarssymbolintervalbarsback-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamtickbarssymbolintervalbarsback-get-openapi.md
- name: Tradestation API - Stream Quote Changes
  x-api-slug: streamquotechangessymbols-get
  description: |-
    Streams the latest Quote information for the given Symbols. The first chunk in the stream is a full quote snapshot - subsequent chunks only contain fields of the quote object that have changed since the last chunk.

    An invalid symbol name will result in a response of this form - {"Symbol":"BADEXAMPLESYMBOL","Error":"FAILED, EX_INVALID_SYMBOL"}

    If the user is not entitled for the symbol requested, response will be of this form - {"Symbol":"EXAMPLESYMBOL","Error":"FAILED, EX_NOT_ENTITLED"}
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotechangessymbols-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotechangessymbols-get-openapi.md
- name: Tradestation API - Stream Quote Snapshots
  x-api-slug: streamquotesnapshotssymbols-get
  description: |-
    Streams the latest Quote for the given Symbols. Each chunk is a full quote object.

    An invalid symbol name will result in a response of this form - {"Symbol":"BADSYMBOLEXAMPLE","Error":"FAILED, EX_INVALID_SYMBOL"}

    If the user is not entitled for the symbol requested, response will be of this form - {"Symbol":"EXAMPLESYMBOL","Error":"FAILED, EX_NOT_ENTITLED"}
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotesnapshotssymbols-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotesnapshotssymbols-get-openapi.md
- name: Tradestation API - Stream BarChart - Starting on Date
  x-api-slug: streambarchartsymbolintervalunitstartdate-get
  description: Streams barchart data starting from startDate, each bar filling quantity
    of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdate-get-openapi.md
- name: Tradestation API - Stream BarChart - Date Range
  x-api-slug: streambarchartsymbolintervalunitstartdateenddate-get
  description: Streams barchart data starting from startDate to end date, each bar
    filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdateenddate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdateenddate-get-openapi.md
- name: Tradestation API - Stream BarChart - Bars Back
  x-api-slug: streambarchartsymbolintervalunitbarsbacklastdate----get
  description: Streams barchart data starting from a number of bars back from last
    date, each bar filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitbarsbacklastdate----get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitbarsbacklastdate----get-openapi.md
- name: Tradestation API - Stream BarChart - Days Back
  x-api-slug: streambarchartsymbolintervalunit-get
  description: Streams barchart data starting from a number of days back from last
    date, each bar filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunit-get-openapi.md
- name: Tradestation API - Stream Tick Bars
  x-api-slug: streamtickbarssymbolintervalbarsback-get
  description: Streams tick bars data from a number of bars back, each bar returned
    separated by interval number of ticks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamtickbarssymbolintervalbarsback-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamtickbarssymbolintervalbarsback-get-openapi.md
- name: Tradestation API - Stream Tick Bars
  x-api-slug: streamtickbarssymbolintervalbarsback-get
  description: Streams tick bars data from a number of bars back, each bar returned
    separated by interval number of ticks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamtickbarssymbolintervalbarsback-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamtickbarssymbolintervalbarsback-get-openapi.md
- name: Tradestation API - Stream Tick Bars
  x-api-slug: streamtickbarssymbolintervalbarsback-get
  description: Streams tick bars data from a number of bars back, each bar returned
    separated by interval number of ticks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamtickbarssymbolintervalbarsback-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamtickbarssymbolintervalbarsback-get-openapi.md
- name: Tradestation API - Stream BarChart - Days Back
  x-api-slug: streambarchartsymbolintervalunit-get
  description: Streams barchart data starting from a number of days back from last
    date, each bar filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunit-get-openapi.md
- name: Tradestation API - Stream BarChart - Days Back
  x-api-slug: streambarchartsymbolintervalunit-get
  description: Streams barchart data starting from a number of days back from last
    date, each bar filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunit-get-openapi.md
- name: Tradestation API - Stream BarChart - Bars Back
  x-api-slug: streambarchartsymbolintervalunitbarsbacklastdate----get
  description: Streams barchart data starting from a number of bars back from last
    date, each bar filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitbarsbacklastdate----get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitbarsbacklastdate----get-openapi.md
- name: Tradestation API - Stream BarChart - Bars Back
  x-api-slug: streambarchartsymbolintervalunitbarsbacklastdate----get
  description: Streams barchart data starting from a number of bars back from last
    date, each bar filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitbarsbacklastdate----get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitbarsbacklastdate----get-openapi.md
- name: Tradestation API - Stream BarChart - Date Range
  x-api-slug: streambarchartsymbolintervalunitstartdateenddate-get
  description: Streams barchart data starting from startDate to end date, each bar
    filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdateenddate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdateenddate-get-openapi.md
- name: Tradestation API - Stream BarChart - Date Range
  x-api-slug: streambarchartsymbolintervalunitstartdateenddate-get
  description: Streams barchart data starting from startDate to end date, each bar
    filling interval of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdateenddate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdateenddate-get-openapi.md
- name: Tradestation API - Stream BarChart - Starting on Date
  x-api-slug: streambarchartsymbolintervalunitstartdate-get
  description: Streams barchart data starting from startDate, each bar filling quantity
    of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdate-get-openapi.md
- name: Tradestation API - Stream BarChart - Starting on Date
  x-api-slug: streambarchartsymbolintervalunitstartdate-get
  description: Streams barchart data starting from startDate, each bar filling quantity
    of unit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streambarchartsymbolintervalunitstartdate-get-openapi.md
- name: Tradestation API - Stream Quote Snapshots
  x-api-slug: streamquotesnapshotssymbols-get
  description: |-
    Streams the latest Quote for the given Symbols. Each chunk is a full quote object.

    An invalid symbol name will result in a response of this form - {"Symbol":"BADSYMBOLEXAMPLE","Error":"FAILED, EX_INVALID_SYMBOL"}

    If the user is not entitled for the symbol requested, response will be of this form - {"Symbol":"EXAMPLESYMBOL","Error":"FAILED, EX_NOT_ENTITLED"}
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotesnapshotssymbols-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotesnapshotssymbols-get-openapi.md
- name: Tradestation API - Stream Quote Snapshots
  x-api-slug: streamquotesnapshotssymbols-get
  description: |-
    Streams the latest Quote for the given Symbols. Each chunk is a full quote object.

    An invalid symbol name will result in a response of this form - {"Symbol":"BADSYMBOLEXAMPLE","Error":"FAILED, EX_INVALID_SYMBOL"}

    If the user is not entitled for the symbol requested, response will be of this form - {"Symbol":"EXAMPLESYMBOL","Error":"FAILED, EX_NOT_ENTITLED"}
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotesnapshotssymbols-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotesnapshotssymbols-get-openapi.md
- name: Tradestation API - Stream Quote Changes
  x-api-slug: streamquotechangessymbols-get
  description: |-
    Streams the latest Quote information for the given Symbols. The first chunk in the stream is a full quote snapshot - subsequent chunks only contain fields of the quote object that have changed since the last chunk.

    An invalid symbol name will result in a response of this form - {"Symbol":"BADEXAMPLESYMBOL","Error":"FAILED, EX_INVALID_SYMBOL"}

    If the user is not entitled for the symbol requested, response will be of this form - {"Symbol":"EXAMPLESYMBOL","Error":"FAILED, EX_NOT_ENTITLED"}
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotechangessymbols-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotechangessymbols-get-openapi.md
- name: Tradestation API - Stream Quote Changes
  x-api-slug: streamquotechangessymbols-get
  description: |-
    Streams the latest Quote information for the given Symbols. The first chunk in the stream is a full quote snapshot - subsequent chunks only contain fields of the quote object that have changed since the last chunk.

    An invalid symbol name will result in a response of this form - {"Symbol":"BADEXAMPLESYMBOL","Error":"FAILED, EX_INVALID_SYMBOL"}

    If the user is not entitled for the symbol requested, response will be of this form - {"Symbol":"EXAMPLESYMBOL","Error":"FAILED, EX_NOT_ENTITLED"}
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tradestation_logo_285x40.png
  humanURL: http://www.tradestation.com
  baseURL: https://api.tradestation.com//v2
  tags: Technology, Financial Services, Financial, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotechangessymbols-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/streams/master/_listings/tradestation/streamquotechangessymbols-get-openapi.md
x-common:
- type: x-website
  url: http://www.tradestation.com
- type: x-api-gallery
  url: http://tigertext.api.gallery.streamdata.io
- type: x-api-stack
  url: http://tradestation.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/tradestation-technologies
- type: x-developer
  url: https://developer.tradestation.com/
- type: x-documentation
  url: https://tradestation.github.io/api-docs/
- type: x-faq
  url: https://www.tradestation.com/faq/
- type: x-github
  url: https://github.com/tradestation
- type: x-openapi
  url: https://tradestation.github.io/api-docs/swagger.json
- type: x-pricing
  url: https://www.tradestation.com/pricing/
- type: x-twitter
  url: https://twitter.com/TradeStation
- type: x-website
  url: https://www.tradestation.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---