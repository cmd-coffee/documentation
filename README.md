### About cmd.coffee
We provide a simple REST API to order high-end, micro roasted coffee. It is in the early stages so expect the API to change and please forgive us for any inconvenience. Thankfully the roasting side of the business has been around since 2010, so even though the API is a little rough around the edges, the coffee quality is consistently exceptional. 

We also have some CLIs in the works. Technically we've only started coding one. It's in crystal. We think its pretty cool. We'll post it as an open-source project when it's less embarrassing.

[In the meantime, check out the current API](https://api.cmd.coffee/swagger/index.html)

### Workflow
1. Join
2. View products
3. Post order-request
4. Pay via cryptocurrency
5. Wait
6. Drink and enjoy
7. Repeat 2-6

#### Join
Before ordering, you need an access-key. You get this by joining. To join, you need an invite-code. Right now we are inviting people privately.

Keep your access-key safe and store it someplace reliable like a post-it on your monitor. Better yet, store it using a secure service like LastPass or 1Password. It cannot be reset and we can't get it. You need it to access your order history and check the status of any outstanding orders.

#### View Products
Yup. Do that. See what pops out. We have some standard blends which are always available, like "meeting day" and "the stand up." We think the names speak for themselves, but you can always read the description and tasting-notes to get more info. We also have single-origin options, which are rotated regularly. With an ever changing menu, its important to keep an open mind to life with many flavor profiles.

#### Request Order
You'll need your Access-Key for this. Send us the product-key and an address. We'll respond with an order-key and payment options.

#### Pay via Cryptocurrency
It is your responsibility to send the funds before the order expires. In case you are unable to send the money, the order will be canceled.

#### Wait
Once we receive payment, we work on getting the coffee to you. If what you ordered is freshly roasted and ready to go, we'll send it out immediately. In case we need to roast it, we'll do that, then send it out the next business day.

#### Drink and enjoy
This is the fun part. You'll need a scale, a burr grinder and brewing device of some sort.

#### Repeat 2-6
The shelf life of coffee is about 3 weeks. A single person drinking about 2 cups of coffee a day will use up 12oz in about 2 weeks. If we were this person, we would order coffee a week before running out, which would be about a week after it was opened.

### FAQs
1. Is your coffee organic?
> While we frequently have beans that are organically grown, our roasting process and facilities are not organically certified. 

2. Do you have a dark roast?
> In order to preserve the original tasting notes of each bean, we roast light-medium. However, we have beans that have a rich mouthfeel and other qualities that seem "dark." If you want a "dark roast" try out the "Meeting Day" blend.

3. How do you calculate sales tax and shipping?
> Shipping is included in the price you see in the product listing. There is no sales tax on coffee beans.

4. How long does it take to get my coffee?
> Shipping takes 1-3 days. Orders are shipped the next business day if the coffee is freshly roasted. Otherwise it will be sent the next business day after roasting. 

5. How do I get order status and tracking info?
> Use the order endpoint with your order-key to see status and tracking info (if available).

6. Can you grind the coffee for me?
> Once coffee is ground it goes stale in about 15 minutes. In order to ensure you have the best coffee experience, we ship our beans whole.

7. Where is your coffee roasted?
> The coffee is roasted in New York.

8. I lost my Access-Key, can you help me?
> Maybe. If all your orders have been received, you can rejoin with your invite-code. If you sent us money and there is a problem with your order, you can send us an email at support@cmd.coffee. Please supply all the information you have about the order, like shipping address, product you ordered and payment info.

9. Where do you ship coffee?
> We currently ship coffee in the US via Priority Mail.

10. Do I have to use cryptocurrency?
> Yes.

11. What is your return policy?
>All sales are final. If you need support with an order please contact us at support@cmd.coffee.

12. I need to cancel my order, what can I do?
>We do not currently support canceling an order once payment has been received. Figuring this out is on our todo list!
