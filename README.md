# Automated ASA deployment on AWS with Ansible 

With the current situation enabling remote access . One way to quickly do that is through the Cisco ASA, once deployed

The virtual ASA appliance - ASAv for short has recently become very popular with enterprises looking to deploy quick capacity, we’ve seen good expamples of this with some enterprises deploying in AWS and Azure

That process for deploying within the cloud systems can be quite clunky

In this guide we’re going to show a way to automate much of that deployment to allow you to quickly spin up ASA capabilities as required and potentially even automate much of the actual on the box deployment for enabling features like Anyconnect VPN's. Using ansible and playbooks we’re going to automate much of the deployment process

Disclaimer: 
