---
title: "Product Manager, or Product Experience Manager?"
date: "2013-05-25"
categories: 
  - "careerbloom"
  - "general"
  - "product-management"
tags: 
  - "product-experience"
---

![](images/052513_1301_productmana1.jpg)In my last post [**Experiencing the product, or productizing the experience?**](http://careermanagement.wordpress.com/2013/05/12/experiencing-the-product-or-productizing-the-experience/), I talked about my experience with SiteZ and how their overall experience left much to be desired even though the core product was good enough. In this post, I will try to analyze things that went wrong which shouldn't have.

Here are 5 things that went wrong for SiteZ if I look from a customer's perspective:

1. They misled the user about the time it takes to register.
2. They didn't allow the user to abort the registration attempt gracefully (which left the email address behind and created rest of the mess).
3. They were not forthcoming about who is sending me these spam emails (the email address was hidden with a display name that was the advertiser's).
4. They exposed a feature to me (unsubscribe) which didn't work
5. They didn't give me an easy way to delete my account – emails bounced, UI didn't have a button to delete, etc.

It is easy to jump to the conclusion that the feature designers have a malicious intention: somehow get people's email id and keep spamming them. However, let's assume that is not the case, and that this is a case of incremental features ruining a product. With this assumption in mind, let's proceed to analyze how each of these situations came to be:

1. **Misleading ad** - Assuming it was not intentional, there are 2 possibilities:
    
    1. Marketing person would have asked someone in products about whether it can be done in 30 seconds, and someone said yes.
    2. Marketing person asked to tweak the flow to make it finish (with basic details) in 30 seconds, but the development team didn't do the work and instead reused the longer flow.
2. **No graceful registration abort** – This is purely a feature design or prioritization issue, probably they didn't think abort is an important use case.
3. **Spam mail identity** – I think the assumption would be that these mails go out after user has agreed to be spammed, so they would know (this information is anyway mentioned at the bottom of the mail in small fonts.
4. **Unsubscribe not working** – Again, feature prioritization issue. Not having unsubscribe button is probably illegal in such spams, so the next best thing was to not code the functionality.
5. **Can't delete account** – A feature prioritization issue. Account deletion is usually an expensive operation (complicated to implement and get it right, and heavy on processing) and so someone somewhere decided it was not important.

A question that comes up: are we talking about one feature, one product, or one experience? Should the feature designer of registration flow worry about spam mail identity? Aren't these very distinct features?

Yes, they are indeed distinct features. At the same time, they need to co-exist peacefully, without causing troubles for each other. SiteZ is one big product, which has multiple features in it which need to plug into each other, and play well with each other. However, if we say SiteZ is a product, it becomes hard to explain #1 above: who should be responsible for advertiser misleading the user. **This is the reason why I would like to think of SiteZ as one big experience.** Advertising is just augmenting the experience, or in some cases act as the invitation to try the experience. If a restaurant's brochure misleads the customer and entices him with a 30% discount, which turns out to be only 10%, it is still a problem for the restaurant.

So who is responsible for SiteZ product experience? Enter [Product Management](http://en.wikipedia.org/wiki/Product_management) team (see this [discussion thread](http://community.productnation.in/beta/discussion/topics/588689/messages?page=1) too). I would like to think it will be Chief Product Officer or VP – Product Management who has ultimate responsibility for the experience. Is it fair to product management team to have such a broad charter? I think it is fair, because the organization needs it and there is no group better positioned to do this.

To recap, here is what we have established so far:

1. SiteZ had multiple features and services dysfunctional which combined to give a terrible overall experience.
2. Even though they are diverse features and services, in the interest of the customer, overall SiteZ experience needs to be treated as one big product experience.
3. The group that owns this one big product experience is Product Management team. They are in the best position to do so

In the next post, we will see how a product management team should have operated so that such issues can be minimized/avoided. Stay tuned!

_Photo Credit: freedigitalphotos.net_
