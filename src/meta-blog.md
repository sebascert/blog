---
title: "Hosting a Blog for Free as a Student"
# menu_order:
post_status: publish
post_excerpt: "Guide on how to host a wordpress page for free as a student."
post_date: 2025-09-26
comment_status: closed
# page_template:
stick_post: no
taxonomy:
  category: ["Guides", "Blogging", "Student Resources"]
  post_tag: ["WordPress", "Azure", "GitHub Student Pack"]
---

[gsp]: https://education.github.com/pack
[awq]: https://learn.microsoft.com/en-us/azure/app-service/quickstart-wordpress
[cda]: https://learn.microsoft.com/en-us/azure/app-service/quickstart-wordpress

If you can prove you are a student to the eyes of Github, then you have a free
option for hosting your own blog. All you have to do is register up for the
[github student pack][gsp], and make use of the Azure cloud resources it comes
with, along with the free domain from one of the DNS providers.

Then you can follow [Azure's wordpress quickstart][awq] guide to quickly set up
wordpress with a few configurations, and point your domain to your newly created
page with the guide on configuring a
[custom domain in Azure's app service][cda].

Just make sure to cancel your domain renewal in a year to avoid charges, as
Azure doesn't require a credit card, you don't have to worry about that.
