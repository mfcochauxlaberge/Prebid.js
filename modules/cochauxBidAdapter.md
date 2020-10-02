# Overview

```
Module Name: Cochaux Bidder Adapter
Module Type: Bidder Adapter
Maintainer: prebid@example.com
```

# Description

Module that connects to Cochaux's demand sources.

# Test Parameters

```
var adUnits = [
    {
        code: "/19968336/header-bid-tag-0",
        mediaTypes: {
            banner: {
                sizes: [[300, 250]],
            },
        },
        bids: [
        {
            bidder: "chx",
            params: {
            placementId: 123,
            publisher: "Publisher",
            domain: "publisher.example.com",
            },
        },
        ],
    },
];
```