---
title: "Why You Should Consider Getting Your Own ASN"
date: "2024-08-31T10:19:14+02:00"
draft: false
series: "Peering into the Network: A BGP Series"
tags: ["Autonomous System", "BGP", "Networking", "Internet Infrastructure", "IPv6", "RIPE NCC", "ASNs"]
---

## Introduction: Why Own an Autonomous System (AS)?

In this series, we'll explore the journey to acquiring and managing your own Autonomous System (AS). Whether you're a tech enthusiast curious about the inner workings of the internet, or an individual frustrated with your ISP's limitations, this series is designed for you.

We'll start with the basics—understanding what an AS is, why you might want one, and the steps involved in obtaining it. By the end of this series, you’ll have the knowledge to establish your own AS, manage your IP resources, and optimize your network's connectivity and performance.

This series is particularly relevant in 2024, where, despite technological advancements, challenges like the slow adoption of IPv6 still persist. We’ll navigate through these challenges together, equipping you with the tools and understanding to take control of your network's destiny.

### Target Audience

This series is intended for tech enthusiasts and individuals who are interested in learning more about networking and internet infrastructure. Whether you’re just starting to dive into the technical aspects of the internet or you’re looking to expand your knowledge, this series offers valuable insights.

### Prerequisites or Assumed Knowledge

While you don’t need to have any prior knowledge of BGP (Border Gateway Protocol), a basic understanding of networking concepts like IP addresses and routing will help you get the most out of this series. We’ll explain the more complex concepts as we go, so you can follow along even if you’re new to this topic.

## Reasons to Consider Your Own ASN

The obvious question is, "Why would you want your own Autonomous System (AS)?" For me, the most compelling reason was the challenge—understanding what it takes to obtain an AS, what it entails, and whether it offers capabilities beyond those of a typical network setup.

This journey was driven by a desire to deepen my knowledge of how the internet operates at a fundamental level.

A secondary motivator, albeit a frustrating one, was the realization that in 2024, my ISP still does not offer IPv6 connectivity. They promise it’s coming, but that’s been the promise for years.

> **Note:** 
> Yes, I could have checked this beforehand, but honestly, it's 2024! Shouldn't IPv6 be standard by now, especially when ISPs offer symmetric FTTH with speeds up to 8 Gbit/s?

## Reasons You Might *Not* Want Your Own ASN

In Europe, under the jurisdiction of the RIPE NCC, acquiring an AS requires associating your name or company with your AS and IP subnets. The process involves signing a standard service contract with a sponsoring LIR (Local Internet Registry), which also requires identity verification.

## Understanding ASN: A Quick Overview

An Autonomous System Number (ASN) is a globally unique identifier assigned to an AS, a network or group of networks under the control of a single entity, presenting a unified routing policy to the internet. ASNs are crucial for exchanging routing information between different networks, ensuring efficient data flow.

Organizations need an ASN if they connect to multiple networks (typically via multiple ISPs) and wish to manage their routing independently. With an ASN, you can establish custom routing policies, participate in BGP routing, and maintain optimal data flow across the internet.

## What to Expect on This Journey

With an understanding of the *why* and *what*, here’s what we’ll explore on the journey to setting up your own AS and acquiring IPv6 netblocks:

- Finding a LIR (Local Internet Registry) to sponsor your AS
- Requesting and obtaining your AS
- Initial connectivity setup for your AS
- Using BGP to announce your prefix
- Transporting your prefix to a location of your choice (e.g., using WireGuard)
- Joining an IXP (Internet Exchange Point)
- Correcting your geolocation data
- Expanding your upstream providers
- Configuring reverse DNS (rDNS) for your prefix

## Conclusion: Join Us on the Journey

By the end of this series, you'll have gained a deeper understanding of how the internet works, and you'll be equipped with the knowledge to set up and manage your own AS. Whether you're looking to enhance your technical skills or simply satisfy your curiosity, this journey will provide valuable insights into the world of internet infrastructure.

Stay tuned for the next installment, and don’t hesitate to reach out with any questions or comments along the way. Let's dive into the fascinating world of Autonomous Systems together!

