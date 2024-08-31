---
title: "Acquiring your AS"
date: "2024-09-01T10:19:14+02:00"
draft: false
series: "Peering into the Network: A BGP Series"
tags: ["Autonomous System", "BGP", "Networking", "Internet Infrastructure", "IPv6", "RIPE NCC", "ASNs"]
---
So you have dec

So you have decided that you want to have your own AS and you want to start the journey. 

> **A word of warning:** This journey can become quiet expensive over the time. Please be aware of this.

Since 2024 RIPE decided that an AS and PI (Provider Independant) IP resrouces will be invoiced with 50€ (each) to the LIR.
This results in at least 100€ fixed costs per year for this experiment. If you want more subnets and a VM with access to BGP sessions, you can add another 100€ per year.


## What do I need?
Before you can begin, you need a LIR (Local internet Registry) to sponsor your resources. This is the easiest and cheapest way to get your AS. (You could become as RIPE member which costs 1.500€+)

There are plenty of LIRs available and you can basically choose any of them to get your AS. Most important, please make sure they are actually are a [RIPE member](https://www.ripe.net/membership/member-support/list-of-members/)

For my journey i chose UK based [lagrange cloud](https://lagrange.cloud/next-level-networking). As of today they offer to set up your AS for a 15£ flat fee. Additionally, I found their documentation really easy to understand, even if you have no prior knowledge about networking.

Their expansive documentation guides you through the process of registering your RIPE account and creating required resources. 

After you ordered your AS and filled in all information according to their documentation, you have to verify your ID. This is as simple as it gets and usually does not require any explanation. 
Once your ID is verified and lagrange has checked everything, they will send you a docusign document to digitally sign the contract. Sign the contract and confirm you've done it in their cloud console/ticket.

The whole process can take a week or two so please be patient. 

This is everything you need to do, to get your own AS and your very first subnet. Wait for the next entry in this journey to see what is required to get the subnet working.

