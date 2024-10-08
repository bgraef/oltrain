---
title: "Use and Configure CoreDNS"
date: 2024-09-27
draft: false
summary: "Learn how to use and configure CoreDNS with Oracle Cloud Native Environment."
tags: ["ocne", "ocne2", "lab", "tutorial", "ocne-k8s"]
showDate: true
---

## Links

:crescent_moon: [Lab](https://luna.oracle.com/lab/bdf64a85-fef5-485e-b7f1-67cb3c5820f3)

:spiral_notepad: [Tutorial](https://docs.oracle.com/en/learn/ocne-coredns)

## Details

Dynamic Name System (DNS) provides a way to translate hostnames to IP addresses for systems located anywhere on your network or the Internet. CoreDNS provides the same DNS service within your Kubernetes cluster to ensure that all deployments on your Kubernetes cluster have a reliable communication mechanism between the pods and services it uses. CoreDNS resolves requests for hostnames to IP addresses within the Oracle Cloud Native Environment cluster.

### Objectives

In this tutorial, you will learn:

- How to configure and use CoreDNS
- Where to locate the CoreDNS configuration files and how to alter them

### Prerequisites

- Installation of Oracle Cloud Native Environment
   - a single control node and single worker node
