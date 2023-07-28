---
layout: post
title:  "Camo for Military"
date:   2020-07-05 00:00:00 -0000
categories: ios
featured_img: /assets/images/camoformilitary.jpg
tags:
  - ios
  - swift
  - swift-ui
  - core-data
  - api
  - rest
---

[Camo for military](http://web.archive.org/web/20230710000124/https://apps.apple.com/us/app/camo-for-military/id1521044940?platform=ipad) was a functional prototype that I and my colleagues built while working at Camo Platforms. It was a military readiness app that allowed soldiers to track inventory and site support tickets. It was built using Swift and SwiftUI, and used Core Data for local storage+caching. It also used a REST API to communicate with the backend.

Features:
* Inventory tracking (Items can be transferred between users)
* Site support tickets (Users can create tickets, and can receive responses from the site support team)
* Hierarchy (Users can see their superiors)
* User profiles (Users can create and see their own profile)
* Chatbot (Users can ask the chatbot questions, and it will respond with answers using AWS Lex)
* Training (Users can see training videos, and read training documents via an in-app pdf viewer)
* News (Admins can create news posts, and users can see them. The news posts are rendered markdown and can contain images, videos, and text)

What I learned:
* How to use SwiftUI (this was my first professional SwiftUI project)
* How to use Core Data with SwiftUI
* Combine!
* How to communicate and collaborate with backend developers to design APIs that suit both the frontend and backend.
* Agile/Scrum, using Jira.

What I would do differently (today):
* I wouldn't use SwiftUI at that same point in time. It was too new, and too buggy. I would have used UIKit instead. (I would use SwiftUI today, but not back then)
* I would be more orthodox in my MVVM use. The database can be a great intermediary between the APIs and the views.
* I would be more consistent with padding and margin sizes, and other layout-related things. The values in the app were just kind of what looked good to us at the time.