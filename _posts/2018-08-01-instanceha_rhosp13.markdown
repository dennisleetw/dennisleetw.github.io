---
layout: post
title:  "Instance HA"
description: Instance HA (High Availability) allows Red Hat OpenStack Platform to automatically evacuate and re-spawn instances on a different Compute node when their host Compute node fails. Instance HA works on shared storage or local storage environments, which means that evacuated instances maintain the same network configuration (static IP, floating IP, and so on) and the same characteristics inside the new host, even if they are spawned from scratch. This article describes how to implement and test Instance HA on RHOSPv13 using TripleO. In this scenario, ceph is used as the shared storage.
img: Logo_RH_OpenStackPlatform_RGB_Gray.png
categories: [one, two]
color: A3E3E3
author: dennis.lee
---

<iframe src="https://docs.google.com/document/d/e/2PACX-1vTabgNBZdhg9Ho07Wuws-lo6QNCoXqX-w3GAfKvQejVHH9l-DYZaihany-qq7A6bNH8973wq4wKgnnW/pub?embedded=true"></iframe>
