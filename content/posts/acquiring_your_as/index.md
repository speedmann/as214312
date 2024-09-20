---
title: "Acquiring Your Autonomous System (AS)"
date: "2024-09-01T10:19:14+02:00"
draft: false
series: "Peering into the Network: A BGP Series"
tags: ["Autonomous System", "BGP", "Networking", "Internet Infrastructure", "IPv6", "RIPE NCC", "ASNs"]
---

Embarking on the journey to obtain your own Autonomous System (AS) is a significant step in enhancing your network capabilities. However, it's important to note that this venture can become quite costly over time.

> **Important Notice:** The financial commitment associated with maintaining an AS can increase as you expand your resources. Please consider this before proceeding.

## What is an Autonomous System (AS)?

An Autonomous System (AS) is a collection of IP networks and routers under the control of a single organization that presents a common routing policy to the internet. Owning an AS provides you with more control over your routing, especially if you manage a large or multi-homed network.

## Cost Considerations

As of 2024, RIPE NCC has implemented a fee structure for AS and Provider Independent (PI) IP resources. Each resource incurs a charge of €50 per year, payable by the sponsoring Local Internet Registry (LIR). Consequently, you should anticipate at least €100 in annual fixed costs for this endeavor. If you require additional subnets or a virtual machine (VM) with access to BGP sessions, expect to incur an additional €100 annually.

In addition to the initial and annual fees for the AS and PI resources, consider potential costs for IP address space, equipment, and possible peering agreements. Running BGP sessions might also require investments in hardware or virtual routers.

## Prerequisites

Before you begin the process, you'll need a Local Internet Registry (LIR) to sponsor your resources. This is generally the most cost-effective and straightforward way to obtain an AS. While you could opt to become a RIPE member yourself, this comes with a significant cost of over €1,500.

There are numerous LIRs to choose from, but it's crucial to ensure that the LIR you select is a verified [RIPE member](https://www.ripe.net/membership/member-support/list-of-members/). When selecting a Local Internet Registry (LIR), consider not only their RIPE membership but also their support quality, cost transparency, and service level agreements (SLAs). A good LIR will provide clear documentation, responsive customer support, and reliable services.

For my own journey, I selected the UK-based provider [Lagrange Cloud](https://lagrange.cloud/next-level-networking). As of today, they offer AS setup services for a flat fee of £15. Their extensive documentation is particularly user-friendly, even for those without prior networking experience.

Lagrange Cloud's documentation guides you through the process of registering your RIPE account and creating the necessary resources. After placing your order and completing the documentation, you will need to verify your identity. This process is straightforward and typically requires minimal explanation.

Once your identity is verified and Lagrange Cloud has reviewed your application, they will send you a DocuSign document to digitally sign the contract. After signing, you’ll need to confirm the completion of this step in their cloud console or via a support ticket.

Please note that the entire process may take one to two weeks, so patience is essential.

## Next Steps

After acquiring your AS, your next steps will include configuring your BGP sessions, establishing peering agreements, and setting up monitoring and management processes to ensure your AS operates smoothly. It's important to regularly review your routing policies and stay informed about network security best practices.

Stay tuned for the next entry in this series, where we will explore the steps required to get your subnet up and running.


