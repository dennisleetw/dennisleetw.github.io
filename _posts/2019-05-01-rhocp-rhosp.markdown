---
layout: post
title:  "PaaS on IaaS"
description: If you are fancy about having a single platform that could host not only VM but also baremetal as well as container, you've got to read this :). In my previous post, I have shared that Red Hat Openstack Platform (RHOSP) supports multi-tenancy BMaaS (credit goes to blog post by Chris Janiszewski). The missing piece of the puzzle is containers which can be addressed by Red Hat Containers Platform (RHOCP - Openshift). RHOCP and RHOSP is a powerful combo because RHOSP as the IaaS is capable of offering many value added services to be consumed by RHOCP with the likes of LBaaS (powered by Octavia), Heat stack, Manila, etc. Openshift can also be deployed seamlessly on RHOSP using Ansible. This article describes the simple procedure to deploy RHOCPv3.11 on RHOSPv13 (Queens) and how application can be provisioned without involving the administrator of infrastructure to prepare the virtual resources upfront.
img: rhocp_rhosp.png
categories: [one, two]
color: FFEFD5
author: dennis.lee
---
<iframe src="https://docs.google.com/document/d/e/2PACX-1vQSDV_qDxOH6txoAWy5KBo_3RPqsAEBJDzM-owzo5Eq9cIWNHvqaG-AGFRN04GvuJ6_Yv_cpFOefe_z/pub?embedded=true"></iframe>
