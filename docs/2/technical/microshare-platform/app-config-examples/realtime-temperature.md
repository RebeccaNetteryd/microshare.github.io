---
layout: docs
title: Realtime Temperature App JSON
description: 
toc: true
---

---------------------------------------

The following JSON code serves as an example for a Realtime Temperature App.


{% highlight java %}
{
  "appTitle": "Realtime Temperature",
  "navOptions": [
    {
      "title": "Realtime Desk Availability",
      "link": "https://dapp.microshare.io/apps/view/5e0f8cd22b0000d1c260????"
    },
    {
      "title": "Realtime Room Availability",
      "link": "https://dapp.microshare.io/apps/view/5e2b627d2b000057df94????"
    },
    {
      "title": "Realtime Temperature",
      "link": "https://dapp.microshare.io/apps/view/5e32d4282b0000a8d794????"
    },
    {
      "title": "Trending Environment",
      "link": "https://dapp.microshare.io/apps/view/5de835881d0000dbbc83????"
    },
    {
      "title": "Trending Environment F",
      "link": "https://dapp.microshare.io/apps/view/5e0a72cc2b0000940160????"
    },
    {
      "title": "Trending Air Quality",
      "link": "https://dapp.microshare.io/apps/view/5e0a75502b0000600260????"
    },
    {
      "title": "Trending Refrigerator",
      "link": "https://dapp.microshare.io/apps/view/5e0f6d2a2b0000dcb760????"
    },
    {
      "title": "Trending Access Usage",
      "link": "https://dapp.microshare.io/apps/view/5e0fa0842b00008dc960????"
    },
    {
      "title": "Trending Desk Availability",
      "link": "https://dapp.microshare.io/apps/view/5e0e1f632b00006e4360????"
    },
    {
      "title": "Trending Usage",
      "link": "https://dapp.microshare.io/apps/view/5e0e02e92b0000433960????"
    },
    {
      "title": "Trending Feedback 3",
      "link": "https://dapp.microshare.io/apps/view/5e1742252b00001ce1e2????"
    },
    {
      "title": "Trending Feedback 5",
      "link": "https://dapp.microshare.io/apps/view/5e172aa52b0000656860????"
    }
  ],
  "": "optional parameters",
  "footerLogo": "https://s3.amazonaws.com/cdn.point.io/distribution/product/1_00/footer.png",
  "headerLogo": "https://s3.amazonaws.com/cdn.point.io/distribution/product/1_00/header.png",
  "headerSecondaryLogo": "",
  "getRecType": "io.microshare.fm.master.agg",
  "minIdeal": 69,
  "maxIdeal": 74,
  "convertTempToFahrenheit": true,
  " ": "end optional parameters",
  "dataRecType": "io.microshare.environment.unpacked",
  "dataContext": "general",
  "viewType": "field",
  "fieldName": "temp",
  "fieldUnit": "°F",
  "queryId": "5e14f78246e0fb002850????",
  "selectionOptions": [
    {
      "name": "Boston",
      "floors": [
        {
          "name": "1st Floor",
          "locations": [
            "A",
            "B",
            "C"
          ]
        },
        {
          "name": "2nd Floor",
          "locations": [
            "A",
            "B",
            "C"
          ]
        },
        {
          "name": "3rd Floor",
          "locations": [
            "A",
            "B",
            "C"
          ]
        }
      ]
    },
    {
      "name": "London",
      "floors": [
        {
          "name": "1st Floor",
          "locations": [
            "A",
            "B",
            "C"
          ]
        },
        {
          "name": "2nd Floor",
          "locations": [
            "A",
            "B",
            "C"
          ]
        },
        {
          "name": "3rd Floor",
          "locations": [
            "A",
            "B",
            "C"
          ]
        }
      ]
    }
  ]
}

{% endhighlight %}