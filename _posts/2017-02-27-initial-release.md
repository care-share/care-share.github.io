---
layout: post
title:  "Initial Release"
date:   2017-02-27 12:00:00
categories: update
---
This post is to mark the release of the initial Care Share pilot software.
This software was created to demonstrate an approach for web-based
creation and management of shared plans of care for home healthcare
patients. It was designed to enable primary care providers and home health
care practitioners to easily understand and modify care plans in a
seamless, asynchronous, distributed manner. To learn more about the
mission of this organization and the purpose of this pilot, visit the
[About page](/about/).


The pilot is deployed as a collection of Docker containers that provide
various services needed to support user activities related to care plans.
Visit the [deploy project](https://github.com/care-share/deploy) to find
out how to deploy the Docker environment for local testing. A diagram of
this environment using the "vacareshare.org" domain is pictured below:

<img src="/images/careshare-architecture.png" />

If this system were to be deployed in a production environment, the
architecture would need to change. A notional production architecture
is pictured below:

<img src="/images/careshare-architecture-production.png" />
