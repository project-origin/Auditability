# Project Origin - Auditability

This repository contains the services and value chain clarification for enabling auditability of granular certificates, wallets, registries etc.

## Pat-Let

Granular certificates issued, based on Project Origins will be used in ESG reporting and as certification method for zero or low emission fuels production. For trust to be established and maintained, processes for verification of certificates, registries, external audit and public scrutiny must be in place. As Project Origin is maturing into use in production environments, basic functionality for audiability of a claim, wallet content or a list of granular certificates must be in place. This repository aims to create such functionality.

## Problem

In Project Origins implementation of granular certificates (GC'S), certificates is issued, claimed, slices and transfered into several registries all the while being contained in wallets controlled by owner of certificates or their agents. While a great deal of the systems relies on trust established by protocol, auditability functions is needed for claims to be trusted in processes outside of the GC issuer, registry ecosystem. 

Let's take an exampe:
`An auditor working on ESG report audits for hourly match of electricity consumption and VE production for the company under audit. An GC service provider has established a wallet containing a power purcase agreement for company site consumption and VE productions certificates, sliced to match 24/7 for a full year. The customer controls the wallet, hence:
1. The auditor needs a delegated access to the wallet.
2. The auditor needs to verify the authenticity of certificates by matching a sample or all certificates against a relevant registry.
3. The auditor needs to varify energy amounts and match of claims to audit that this does in fact match the PPA VE production against site consumption 24/7 of the year. If checking a sample leads to no errors, thus is ususally enaugh for the auditor to sign off the reported emissions.`

## Context

Important design criterias for this process is that trust in the auditor relies on hanged mans principle (e.g. loosing her right to work as an auditor), rather than actual proof. The auditor can not be expected to know Project Origin, GC standards specifics or any ways of interacting directly with registries. They will have to be introduced to a simple audit guide including audit services that. Auditors can be expected to be able to handle basic browser based services or otherwise excel sheets or CSV files. It can not be expected that an auditor has data engineers or software engineers available to help.

The only contact or in fact context provided to the auditor is what is given from the customer. Hence easy access to information and services on how to enable an auditor should be provided by a relevant party or parties in the GC ecosystem.

## Forces

## Solution
