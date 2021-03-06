---
title: FAQs
taxonomy:
    category: docs
---

### Can I try Publisher before I buy it?
There is no try before you buy, however, there is a <a href="http://demo.boldminded.com/">live demo site</a> you can play around with before you purchase.

### How do I set the default language of an MSM site?
The officially supported method is to use the <a href="https://boldminded.com/add-ons/publisher-language-control">Publisher Language Control</a> extension.

### How do I use sub-domains or multiple top level domains with Publisher?
The officially supported method is to use the <a href="https://boldminded.com/add-ons/publisher-domain-control">Publisher Domain Control</a> extension.

### How does Publisher save its data?
Publisher saves most of its data to its own custom tables which mimic ExpressionEngine's native ``exp_channel_titles`` and ``exp_channel_data`` tables. Through the use of ExpressionEngine's hooks the data form these tables are used to replace the data from the native tables when displayed on the front-end or within the control panel.

### Does Publisher create duplicate entries for each language?
No. Due to storing its data in its own tables ExpressionEngine is only aware of 1 database row for each entry.

### Does Publisher translate custom field names or Grid columns in the CP?
Publisher will not translate custom field type names, help text, or Grid column titles. Publisher only supports translation of entry content.

### Will Publisher translate entry comments?
No, Publisher does not support translation of entry comments.

### Does Publisher work with X add-on?
This is a hard question to answer, but the first place you should check is the [Requirements](../requirements) and [third-party add-ons](../third-party-addons) pages. If you know the add-on does not save its data in a custom database table, then most likely Publisher supports it. If it saves its data in a custom table, such as the Channel Images add-on, then it may not work with Publisher. If in doubt, [just ask us](mailto:support@boldminded.com).

