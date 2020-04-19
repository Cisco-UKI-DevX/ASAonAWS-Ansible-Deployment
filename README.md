# Automated ASA deployment on AWS with Ansible 

With the current situation enabling remote access . One way to quickly do that is through the Cisco ASA, once deployed the ASA can be flexibily configured to allow for supporting IPSec/SSL remote access VPN's with also the option for IPSec site-to-site to allow you tunnel back into your own headend infrastructure

The virtual ASA appliance - ASAv for short has recently become very popular with enterprises looking to deploy quick capacity, we’ve seen good expamples of this with some enterprises deploying in AWS and Azure and creating a site-to-site tunnel back to their own on-premise datacentres to allow for fast scaling of remote access infrastructure

That process for deploying within the cloud systems can be quite clunky, however is actually a very simple process which we intend to break down here for the reader and then look to automate through common tools such as ansible.

In this guide we’re going to show a way to automate much of that deployment to allow you to quickly spin up ASA capabilities as required and potentially even automate much of the actual on the box deployment for enabling features like Anyconnect VPN's. 

Disclaimer: 

## AWS Prerequisites

## Ansible playbook

### Walkthrough
