---
layout: bidder
title: Fidelity Media
description: Prebid Fidelity Media Bidder Adapter
top_nav_section: dev_docs
nav_section: reference
hide: true
biddercode: fidelity
biddercode_longer_than_12: false
prebid_1_0_supported : true
media_types: banner
gdpr_supported: true
---

### bid params

{: .table .table-bordered .table-striped }
| Name   | Scope    | Description                                      | Example                  | Type     |
|--------|----------|--------------------------------------------------|--------------------------|----------|
| zoneid | required | The ad zone or tag specific ID                   | `'27248'`                | `string` |
| floor  | optional | The floor CPM price for the request              | `0.1234`                 | `float`  |
| server | optional | Bidder domain (default `'x.fidelity-media.com'`) | `'x.fidelity-media.com'` | `string` |
