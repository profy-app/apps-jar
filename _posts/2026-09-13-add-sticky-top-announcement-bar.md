---
layout: post
title: "Shopify tutorial: How to add sticky top announcement bar"
date: 2026-09-13 09:00:00 +0000
permalink: /blog/add-sticky-top-announcement-bar/
excerpt: "Learn how to build a sticky announcement bar in Shopify, customize it for promotions and urgency, and drive more conversions across your store."
---

Sticky announcement banners are one of the easiest ways to grab users’ attention. By creating an announcement bar or banner in your Shopify store, you can:

1. Advertise or promote a product that is offering a discount.
2. Promote a product collection page.
3. Share important text announcements such as “Free shipping for orders above $20”.

Many Shopify themes include a simple announcement bar, but it is not sticky. As a result, users stop seeing it as soon as they scroll down the page. Additionally, customizing its design can be difficult and time-consuming, while code-based solutions often vary by theme.

### Types of announcement bars and banners

<figure>
  <img src="/assets/marquee.webp" alt="Scrolling text / animated announcement bar" loading="eager"        fetchpriority="high"
    decoding="async">
  <figcaption>Scrolling text / animated announcement bar</figcaption>
</figure>

Display large text in a single line with marquee and scrolling text animation.

<figure>
  <img src="/assets/slider_banner.gif" alt="Sliding announcement bar" loading="eager"
  fetchpriority="high" 
  decoding="async">
  <figcaption>Sliding announcement bar</figcaption>
</figure>

Combine multiple announcements in one banner where each slide changes every few seconds.

<figure>
  <img src="/assets/coupon_code_bar.png" alt="Coupon code bar" loading="eager"
  fetchpriority="high" 
  decoding="async">
  <figcaption>Coupon code bar</figcaption>
</figure>

Inform and promote coupon codes through an announcement banner where customers can copy the coupon code with a single click.

### What we will build

In my Shopify store, I have a newly launched product called “LED High Tops” which is being sold at a $20 discount. I want to promote this offer across other store pages to generate more sales.

Hence I need to create a sticky announcement bar with the text “$20 off on LED High Tops” along with an action button that redirects to the destination URL.

We will learn how to create a simple announcement bar and then customize it into an animated scrolling or sliding bar with multiple announcements.

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*UljUN-9-GaYPJm39FVxjoA.png" alt="Shopify product I want to promote" loading="lazy"
    decoding="async">
  <figcaption>Shopify product I want to promote</figcaption>
</figure>

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*cp1h40ScIUW_YRojY4piFA.png" alt="Final result of announcement banner" loading="lazy"
    decoding="async">
  <figcaption>Final result of announcement banner</figcaption>
</figure>

### 1) Install the “Profy Banner & Countdown Timer” Shopify app

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*B-MbYmbPKdUcLSMKk6ysJw.png" alt="Profy app page" loading="lazy"
    decoding="async">
  <figcaption>Profy app page</figcaption>
</figure>

There are many announcement bar apps on Shopify, but I chose **Profy Banner & Countdown Timer** because it combines announcement bars and countdown timers in one app with extensive customization options.

Unlike other apps that require separate solutions for announcement bars and countdown timers, Profy provides everything in a single application.

**Link**: [https://apps.shopify.com/profy-promo-bar](https://apps.shopify.com/profy-promo-bar)

### 2) Enable app embed

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:598/1*6Egg7tlYWPD_VBmfwQyapg.png" alt="Enable app embed" loading="lazy"
    decoding="async">
  <figcaption>Enable app embed</figcaption>
</figure>

After installing the app, enable **App Embed** to display the banners on your storefront.

### 3) Click on Create Banner and select “Announcement”

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*pzD-7yjmQ-7Lm85HryDVkQ.png" alt="Create banner button in dashboard" loading="lazy"
    decoding="async">
  <figcaption>Create banner button in dashboard</figcaption>
</figure>

From the dashboard, click **Create Banner** → select **Top / Bottom Bar** → choose **Announcement Banner** → select **Single Message** to create the initial announcement bar, which can later be updated to animated and sliding versions.

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*6ZTvePEoUygRvQL5YKV9Mg.png" alt="Placement options" loading="lazy"
    decoding="async">
  <figcaption>Placement options</figcaption>
</figure>

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*wlDcBpSwzeAssbdHAIoang.png" alt="Announcement banner option" loading="lazy"
    decoding="async">
  <figcaption>Announcement banner option</figcaption>
</figure>

### 4) Enter a banner message and destination URL

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*VTdPBfJJeN4iBswnsClmNg.png" alt="Banner details section" loading="lazy"
    decoding="async">
  <figcaption>Banner details section</figcaption>
</figure>

On the **Edit Banner** page, enter the **banner name** and update the **banner message, button text, and destination URL**.

### 5) Select target pages and device

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*kCeI97xcInqEKp8NNTC-NQ.png" alt="Single announcement bar" loading="lazy"
    decoding="async">
  <figcaption>Single announcement bar</figcaption>
</figure>

For a single-announcement banner, select **Simple Banner** under **Banner Setup → Announcement Setup → Announcement Type**.

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:1000/1*cgtBFXjLZv4G19Bka9bgeg.png" alt="Configure scrolling text / animated announcement bar" loading="lazy"
    decoding="async">
  <figcaption>Configure scrolling text / animated announcement bar</figcaption>
</figure>

For an animated announcement bar, select **Scrolling Text** as the announcement type and adjust the **animation speed** from slow to fast.

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*-6WNtGP9yu-OuOzYc9nmFw.png" alt="Configure sliding announcement bar" loading="lazy"
    decoding="async">
  <figcaption>Configure sliding announcement bar</figcaption>
</figure>

For multiple announcements in a single bar, select **Sliding Announcement Bar**. Click **Add New Slide** to add announcements with their **content, button type, and destination URL**. Add more slides as needed and adjust **Slide Duration** to control how long each slide is displayed before transitioning.

### 6) Select target pages and device

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*Q7FrDpnAzvqVLu7UGcp-ww.png" alt="Banner targeting options" loading="lazy"
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
  <img src="https://miro.medium.com/v2/resize:fit:700/1*-PbfsX3P8zpWgxGmM0AJNQ.png" alt="Style settings" loading="lazy"
    decoding="async">
  <figcaption>Style settings</figcaption>
</figure>

Customize the banner in **Style Settings** by adjusting **colors, font size, height, templates, and background images** to match your theme.

### 8) Configure banner position

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*mFmLS1Uo7XP7AkfxNquFKQ.png" alt="Visibility settings" loading="lazy"
    decoding="async">
  <figcaption>Visibility settings</figcaption>
</figure>

In **Visibility Settings**, select the banner’s **position (top or bottom)**, enable **sticky display**, and set the **start and end dates**.

For this example, select **Top** and enable **Sticky** to keep the banner fixed at the top of the page.

### 9) Save and view results on the store

<figure>
  <img src="https://miro.medium.com/v2/resize:fit:700/1*cp1h40ScIUW_YRojY4piFA.png" alt="Final result" loading="lazy"
    decoding="async">
  <figcaption>Final result</figcaption>
</figure>

Finally, click **Save** to publish the banner. Verify that it appears on the storefront and that clicking **Buy Now** redirects to the **LED High Tops** product page.

This approach gives you a simple, effective way to advertise specials, highlight collections, or announce important store updates while keeping the customer experience clean and consistent across the storefront.
