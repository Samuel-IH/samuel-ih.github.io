---
layout: post
title:  "Camo for Skyline"
date:   2020-08-08 00:00:00 -0000
categories: ios
featured_img: /assets/images/camoforskyline.jpg
tags:
  - ios
  - swift
  - swift-ui
  - api
  - rest
---

[Camo for Skyline](https://web.archive.org/web/20230710000212/https://apps.apple.com/us/app/camo-for-skyline/id1526900359) was a client for a backend that does some Secret Server Magic™. We built it with SwiftUI, and used URLSession for the networking. The app was built in about two weeks.

Features:
* Login
* Select an image from photo library
* Upload image to backend -- while showing progress
* View location of image on map
* Tracking of image upload history

What I learned:
* How to interact with the Photos using the _newer_ Photos API (I had previously used the older one).
* How to wrap a UIKit view in SwiftUI (Bear in mind that this was before they migrated MapKit to SwiftUI).

What I would do differently (today):
* Add more features? It was a really quick prototype.