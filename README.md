#Current Hiccups
- Still unsure how to send mart emails without giving financial information. I may call them to get their help. 
	- Their site says that Transactional Email is included in a monthly plan, even though they also say "you can access all of our features without spending a cent. You ony pay once you start sending campaigns." Clearly I'm not understanding something, so I will definitely be giving them a call.
- The [link](http://www.campmon.com/yoda/helpcms/Topic?id=1265#attachments) they gave for understanding attachments for the smart emails isn't working. I'll keep searching for alternative documentation.

#What are Transactional Emails?
Any email sent to one person as a result of an action taken by the user - including automated notifications like welcome emails, shipping notices, order confirmations, password reminders, purchase reciepts, etc - basically anthing that isn't a bulk blast. The emails provide feedback, making sure users know that transactions have been processed.

The main idea is the adage, "you're only as strong as your weakest link," so if the user experience on the transactional email side is lacking, strengthen it.


#Basic Requirements
- Can we attach an email through given URL?
- Can we send all monetary values? How flexible is it?
- Can the logo be included in the email?
	- It will be the logos of the actual photographers.

#Benefits of Campaign Monitor
- Options
	- smart email: the content is defined inside Campaign Monitor and is triggered via your applicatoin by supplying recipients and email variables to merge into the content.  
	- classic email: we supply the entire message content at the time of sending.
- There's support for Liquid Templating 
	- Liquid is an [open-source language](https://docs.shopify.com/themes/liquid-documentation/basics) created by Shopify to enable dynamic content. It is supported in our smart transactional email when you import your own email design, allowing you to create invoice item lists, reformat text, show content based on certain conditions and more.
	- For a quick-start guide on Liquid's syntax and capabilities, we recommend [Liquid for designers](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers).

#Cons of Campaign Monitor
- All [/transactional endpoints support only JSON](https://www.campaignmonitor.com/api/transactional/) and are subject to [rate limiting](https://www.campaignmonitor.com/api/getting-started/#rate_limiting)
- Two

##Resources

[Possible Pdf to Send](https://assets2.sendgrid.com/mkt/assets/pdfs/SendGrid_Leveraging_Transactional_Email-00fe5ab0c27cc3441b33121f45f854b5.pdf?mc=Direct)




