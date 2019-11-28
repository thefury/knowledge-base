---
title: "Setting Up Postgresql for Aks"
date: 2019-11-28T17:06:16-05:00
draft: true
---

This is a bit of a pain:

1. Find the name of the vnet on your AKS
2. Add Microsoft.SQL service endpoint to vnet
3. Spin up a database instance - minimum of GP (not basic) sku
4. Add firewall rule for the office
5. Add firewall rule for the vnet
