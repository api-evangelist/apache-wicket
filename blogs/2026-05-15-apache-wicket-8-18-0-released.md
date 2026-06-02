---
title: Apache Wicket 8.18.0 released
url: http://0.0.0.0:4000/news/2026/05/15/wicket-8.18.0-released.html
date: '2026-05-15'
author: ''
feed_url: https://wicket.apache.org/feed
---
The Apache Wicket PMC is proud to announce Apache Wicket 8.18.0! Apache Wicket is an open source Java component oriented web application framework that powers thousands of web applications and web sites for governments, stores, universities, cities, banks, email providers, and more. You can find more about Apache Wicket at https://wicket.apache.org This release marks another minor release of Wicket 8. We use semantic versioning for the development of Wicket, and as such no API breaks are present in this release compared to 8.0.0. New and noteworthy CVE-2026-43646 crafted URLs can bypass PackageResourceGuard CVE-2026-42509 crafted strings can break out of the JavaScript sequence CVE-2026-40010 possible session fixation using AuthenticatedWebSession Using this release With Apache Maven update your dependency to (and don’t forget to update any other dependencies on Wicket projects to the same version): <dependency> <groupId>org.apache.wicket</groupId> <artifactId>wicket-core</artifactId> <version>8.18.0</version> </dependency> Or download and build the distribution yourself, or use our convenience binary package you can find here: Download: http://wicket.apache.org/start/wicket-8.x.html#manually
