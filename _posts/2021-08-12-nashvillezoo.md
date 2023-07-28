---
layout: post
title:  "Nashville Zoo"
date:   2021-08-12 00:00:00 -0000
categories: unity
featured_img: /assets/images/nashvillezoo.jpg
tags:
  - unity
  - ios
  - android
  - swift
  - kotlin
  - api
  - uaal
  - ar
---

Nashville Zoo ([iOS](https://apps.apple.com/us/app/nashville-zoo/id1511574560) and [Android](https://play.google.com/store/apps/details?id=com.blipd.nashvillezoo&hl=en_US&gl=US)) was a project that I helped build while working at Blipd for the Nashville Zoo. It was a tourism app that allowed users to see the zoo map, and see information about the animals. It used UaaL (Unity as a Library) to integrate Unity into the native app for some AR (virtual world) features.

Features:
* Zoo map
* Exhibit and POI information
* AR (virtual world) features
* Virtual collectible animals (that can be fed and interacted with)
* Localized in English and Spanish

What I learned:
* How to use UaaL.
* How to write and use native plugins for iOS (interop between Unity and Swift).
* How to use addressables to manage the hosting and downloading of remote content.
* How to use Unity's AR Foundation.
* A lot about UI in Unity (using UnityUI, not UITK or legacy UGUI).
* Kotlin, the language!
* A lot about editor scripting in Unity.
* How to use localization in both Unity and Xcode.

What I would do differently (today):
* I would use the new Unity UI Toolkit instead of UnityUI.
* I would write some code generators to handle most of the boilerplate for communicating between Unity and the native sides. A plugin had to be written and maintained for each OS that we were targeting and this eventually became a bit tedious.
* Better asset organization. Since then we have established better convention about where to place assets.
