# n8n-templates
low-code n8n security workflows 

This template can be imported into [n8n](https://n8n.io/) by copy/paste the raw code into the canvas. 
The flow will collect samples from [TheHive](https://n8n.io/) and post it to [CAPEv2 sandbox](https://github.com/kevoreilly/CAPEv2) when the tag "sandbox" is added to an
url, domain or file observable. It will return a task with the report URL and the first 2 screenshots back to TheHive, it add some tags to the case and autoclose the task when finished.

prerequisits: enabled webhooks in TheHive4.x.x and enabled restAPI in CAPEv2 
after import add you credentials and API secrets to the credentialstore in N8N inorder to make this work
