---
layout: bidder
title: Adpopcorn
description: Prebid Adpopcorn Bidder Adapter
hide: true
biddercode: adpopcorn
---

### Note

The Adpopcorn bidder adapter requires setup and approval from IGAWorks Adpopcorn team.
Please reach out to <ssp_biz@igaworks.com> for more information.

### Bid Params

{: .table .table-bordered .table-striped }
| Name          | Scope    | Description                      | Example                 | Type            |
|---------------|----------|----------------------------------|-------------------------|-----------------|
| `publisherId` | required | The publisher ID                 | `'web_mtq52yqc33'`      | `string`        |
| `placementId` | required | Identifies specific ad placement | `'web_kn85q5ltwn4ivay'` | `string`        |
| `bcat`        | optional | Blocked IAB Categories           | `['IAB1-5', 'IAB1-6']`  | `Array<string>` |
