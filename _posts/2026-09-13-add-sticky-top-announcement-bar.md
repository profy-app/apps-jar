---
layout: post
title: "Shopify tutorial: How to add sticky top Announcement Bar"
date: 2026-09-13 09:00:00 +0000
permalink: /blog/add-sticky-top-announcement-bar/
excerpt: "Learn how to build a sticky announcement bar in Shopify, customize it for promotions and urgency, and drive more conversions across your store."
---

Sticky announcement banners are one of the easiest ways to grab users’ attention. By creating an announcement bar/banner in your Shopify store, you can:

1. Advertise or promote a product that is offering a discount.
2. Promote a product collection page.
3. Share important text announcements such as “**Free shipping for orders above $20**”.

### Common Uses of an Announcement Bar

1. **Promote Free Shipping** :Highlight your free shipping offer to encourage customers to complete their purchase, such as: **"Free shipping on orders above $20."**
2. **Share Delivery Information**: Set clear delivery expectations by displaying estimated delivery times for specific locations, such as: **"Order now and get delivery in approximately 2–3 days across the US."**
3. **Promote Discounts & Sales**: Announce discounts and direct customers to the relevant products or collections with an action button, such as: **"10% off all T-shirts" → View Collection"**
4. **Promote Coupon Codes:** Display promotional coupon codes directly in the announcement bar to encourage customers to use them at checkout, such as: **"Get 10% off your order with code WELCOME10."** . A dedicated coupon-code banner can make this type of promotion even more effective.
5. **Create Urgency with a Sales Countdown:** Add a countdown timer to promote flash sales and create urgency by showing customers exactly how much time remains before the offer ends.
6. **Announce New Product Launches:** Use the announcement bar to showcase newly launched products or collections and direct customers to them with an action button, such as: **"New arrivals are here!" → Shop New Products**

### How to Create an Announcement Bar Through Your Shopify Theme

Shopify provides a built-in **Announcement Bar** feature in many themes. You can follow [Shopify's official guide](https://help.shopify.com/en/manual/online-store/themes/customizing-themes/common-customizations/add-announcement-banner) to add an announcement bar through the theme editor.

Many Shopify themes offer a simple announcement bar, but it is often **not sticky**. This means customers may stop seeing the announcement as soon as they scroll down the page. Customizing its design and behavior can also be difficult and time-consuming, while code-based solutions may vary depending on the store's theme.

Depending on the theme, you may have options for basic text, links, colors, and multiple rotating announcements. However, more advanced features such as **scrolling/marquee announcements, countdown timers, coupon-code promotions, scheduling, customer or page targeting, animations, and greater design flexibility** may not be available.

For these advanced requirements, a dedicated Shopify announcement bar app can provide more customization without requiring theme-specific code changes.

In this article, we'll use **Profy Banner & Countdown Timer** to create and customize different types of announcement bars for a Shopify store.

### Types of announcement bars and banners

<figure>
  <img src="/assets/marquee.webp" alt="Scrolling text / animated announcement bar" 
  height="28"
  loading="eager"        
  fetchpriority="high"
    decoding="async">
  <figcaption>Scrolling text / animated announcement bar</figcaption>
</figure>

Display large, attention-grabbing messages in a single line using a **scrolling text or marquee animation**. This is useful for showcasing promotions, special offers, free shipping messages, product announcements, and other important store updates without taking up additional vertical space.

For a detailed step-by-step guide, see our dedicated guide on [creating a moving banner and scrolling text marquee section for Shopify.](https://appsjar.net/blog/moving-banner-scrolling-text-marquee-section-shopify/)

<figure>
  <img src="/assets/slider_banner.gif" alt="Sliding announcement bar"
  height="52"
  loading="eager"
  fetchpriority="high" 
  decoding="async">
  <figcaption>Sliding announcement bar</figcaption>
</figure>

Combine multiple announcements into a **single rotating banner**, with each message automatically changing after a few seconds. This allows you to display multiple promotions, offers, shipping information, or store updates without taking up additional space on your storefront.

For a detailed step-by-step guide, read our dedicated guide on [creating a multiple rotating announcement bar for Shopify](https://appsjar.net/blog/multiple-rotating-announcement-bar-shopify/).

<figure>
  <img src="/assets/coupon_code_bar.png" alt="Coupon code bar"
    height="63"
   loading="eager"
  fetchpriority="high" 
  decoding="async">
  <figcaption>Coupon code bar</figcaption>
</figure>

Inform and promote coupon codes through an announcement banner where customers can copy the coupon code with a button click.

### What we will build

In my Shopify store, I have a newly launched product called “**LED High Tops**” which is being **sold at a $20 discount**. I want to promote this offer across other store pages to gather more sales.

Hence I need to create a sticky announcement bar with the **text “$20 off on LED High Tops”** along with an **action button that redirects to the destination URL**.

We will learn how to create a simple announcement bar and then customize it into an animated scrolling or sliding bar with multiple announcements.

<figure>
  <img src="/assets/article1/product_promote.webp" alt="Shopify product I want to promote" loading="lazy"
    decoding="async">
  <figcaption>Shopify product I want to promote</figcaption>
</figure>

<figure>
  <img src="/assets/article1/final_result.webp"
  data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*cp1h40ScIUW_YRojY4piFA.png" alt="Final result of announcement banner" loading="lazy"
    decoding="async">
  <figcaption>Final result of announcement banner</figcaption>
</figure>

### 1) Install the “Profy Banner & Countdown Timer” Shopify app

<figure>
  <img src="/assets/article1/app_homepage.webp" alt="Profy app page" loading="lazy"
    decoding="async">
  <figcaption>Profy app page</figcaption>
</figure>

There are many announcement bar apps on Shopify, but I chose [**Profy Banner & Countdown Timer**](https://apps.shopify.com/profy-promo-bar) because it combines announcement bars and countdown timers in one app with extensive customization options.

Unlike other apps that require separate solutions for announcement bars and countdown timers, Profy provides everything in a single application.

**Link**: [https://apps.shopify.com/profy-promo-bar](https://apps.shopify.com/profy-promo-bar)

### 2) Enable app embed

<figure>
  <img src="/assets/article1/enable_app.webp" alt="Enable app embed" loading="lazy"
    decoding="async">
  <figcaption>Enable app embed</figcaption>
</figure>

After installing the app, enable **App Embed** to display the banners on your storefront.

### 3) Click on Create Banner and select “Announcement”

<figure>
  <img src="/assets/article1/create_banner.webp"
  data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*pzD-7yjmQ-7Lm85HryDVkQ.png"
   alt="Create banner button in dashboard" loading="lazy"
    decoding="async">
  <figcaption>Create banner button in dashboard</figcaption>
</figure>

From the dashboard, click **Create Banner** → select **Top / Bottom Bar** → choose **Announcement Banner** → select **Single Message** to create the initial announcement bar, which will later be updated to animated and sliding versions.

<figure>
  <img src="/assets/article1/placement_option.webp" 
   data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*6ZTvePEoUygRvQL5YKV9Mg.png"
   alt="Placement options" loading="lazy"
    decoding="async">
  <figcaption>Placement options</figcaption>
</figure>

<figure>
  <img src="/assets/article1/banner_option.webp" 
  data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*wlDcBpSwzeAssbdHAIoang.png"
  alt="Announcement banner option" loading="lazy"
    decoding="async">
  <figcaption>Announcement banner option</figcaption>
</figure>

### 4) Enter a banner message and destination URL

<figure>
  <img src="/assets/article1/banner_details.webp"
  data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*VTdPBfJJeN4iBswnsClmNg.png" alt="Banner details section" loading="lazy"
    decoding="async">
  <figcaption>Banner details section</figcaption>
</figure>

On the **Edit Banner** page, enter the **banner name** and update the **banner message, button text, and destination URL**.

### 5) Upgrade single message to Sliding and Animated Announcement bar

<figure>
  <img src="/assets/article1/banner_setup.webp" alt="Single announcement bar" loading="lazy"
    decoding="async">
  <figcaption>Single announcement bar</figcaption>
</figure>

For a single-announcement banner, select **Simple Banner** under **Banner Setup → Announcement Setup → Announcement Type**.

<figure>
  <img src="/assets/article1/scrolling_text.webp"
  data-zoom-src="https://miro.medium.com/v2/resize:fit:2000/format:webp/1*cgtBFXjLZv4G19Bka9bgeg.png"
   alt="Configure scrolling text / animated announcement bar" loading="lazy"
    decoding="async">
  <figcaption>Configure scrolling text / animated announcement bar</figcaption>
</figure>

For an animated announcement bar, select **Scrolling Text** as the announcement type and adjust the **animation speed** from slow to fast.

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*-6WNtGP9yu-OuOzYc9nmFw.png"
  data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*-6WNtGP9yu-OuOzYc9nmFw.png" alt="Configure sliding announcement bar" loading="lazy"
    decoding="async">
  <figcaption>Configure sliding announcement bar</figcaption>
</figure>

For multiple announcements in a single bar, select **Sliding Announcement Bar**. Click **Add New Slide** to add announcements with their **content, button type, and destination URL**. Add more slides as needed and adjust **Slide Duration** to control how long each slide is displayed before transitioning.

### 6) Select target pages and device

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*Q7FrDpnAzvqVLu7UGcp-ww.png"
  data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*Q7FrDpnAzvqVLu7UGcp-ww.png" alt="Banner targeting options" loading="lazy"
    decoding="async">
  <figcaption>Banner targeting options</figcaption>
</figure>

You can customize **banner targeting** to show or hide banners based on:

- **Page URL**
- **Page category**
- **Device type**

In this example, we’ll configure the banner to **hide on the destination product page**.

### 7) Customize banner design based on your Shopify theme

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*-PbfsX3P8zpWgxGmM0AJNQ.png"
  data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*-PbfsX3P8zpWgxGmM0AJNQ.png" alt="Style settings" loading="lazy"
    decoding="async">
  <figcaption>Style settings</figcaption>
</figure>

Customize the banner in **Style Settings** by adjusting **colors, font size, height, templates, and background images** to match your theme.

### 8) Configure banner position

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*mFmLS1Uo7XP7AkfxNquFKQ.png" alt="Visibility settings" loading="lazy"
    data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*mFmLS1Uo7XP7AkfxNquFKQ.png"
    decoding="async">
  <figcaption>Visibility settings</figcaption>
</figure>

In **Visibility Settings**, select the banner’s **position (top or bottom)**, enable **sticky display**, and set the **start and end dates**.

For this example, select **Top** and enable **Sticky** to keep the banner fixed at the top of the page.

### 9) Save and view results on the store

<figure>
  <img src="/assets/article1/final_result.webp"
  data-zoom-src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*cp1h40ScIUW_YRojY4piFA.png"
   alt="Final result" loading="lazy"
    decoding="async">
  <figcaption>Final result</figcaption>
</figure>

Finally, click **Save** to publish the banner. Verify that it appears on the storefront and that clicking **Buy Now** redirects to the **LED High Tops** product page.

This approach gives you a simple, effective way to advertise specials, highlight collections, or announce important store updates while keeping the customer experience clean and consistent across the storefront.
