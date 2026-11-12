---
layout: post
title: "How to Add a Countdown Timer & Clock to Your Shopify Store for Your Next Sale"
date: 2026-11-07 01:00:00 +0000
permalink: /blog/add-countdown-timer-clock-shopify-sale/
excerpt: "Learn how to add countdown timer & clock for your next shopify store sale"
---

## Why Do You Need a Countdown Timer for Your Shopify Store?

1. **Create a Sense of Urgency**: Encourage customers to make quicker purchase decisions by displaying countdown timers alongside discounts and special offers.
2. **Increase Customer Engagement**: Capture customers’ attention with visually appealing countdown timers and encourage quicker purchase decisions.
3. **Promote Flash Sales and Seasonal Offers:** Create time-limited promotions for festivals and special occasions, such as Black Friday, Christmas, and holiday sales.

### Types of Countdown timers

1. **Sale Countdown Timer**: Create countdown timers with specific start and end dates to promote festival and seasonal discounts, such as Halloween, Black Friday, and Christmas sales.
2. **Weekly Recurring Sales**: Set up recurring countdown timers for specific days of the week to promote regular discounts. For example, run a “ **Tenner Tuesday**” campaign where selected products are discounted every Tuesday.
3. **Shipping Deadline Timer**: Display a daily recurring countdown timer to highlight order and shipping deadlines, such as “ **Order within 4 hrs 12 mins for dispatch today.**” This creates urgency and encourages customers to complete their purchases sooner.

### 1) Install “Profy Banner & Countdown Timer” Shopify plugin

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*B-MbYmbPKdUcLSMKk6ysJw.png)

Profy app page

Link: [https://apps.shopify.com/profy-promo-bar](https://web.archive.org/web/20250210230936/https://apps.shopify.com/profy-promo-bar?ref=contact)

The **Profy Banner & Countdown Timer** Shopify app makes it easy to create customizable countdown timer banners and popups for your store. With multiple styling and scheduling options, you can set up engaging countdown timers **without any coding knowledge**.

### 2) Enable App embed

After installing the app, enable the **App Embed** from your Shopify theme editor to ensure the countdown timer displays correctly on your storefront.

![](https://miro.medium.com/v2/resize:fit:598/1*6Egg7tlYWPD_VBmfwQyapg.png)

app embed

### 3) Click on Create Banner and Select “Countdown timer”

To create your first banner, navigate to the app’s **Home page** and click the “ **Create Banner”** button.

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*-b-0paV3_T8p3dFSoU9jFA.png)

Click on Create New Banner

As the first step, choose where you want your banner to appear. You can select from **Top/Bottom Bar**, **Product Page**, **Inside Page Section**, or **Popup**.

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*reZKqqWYDx15caAjQMtZ_w.png)

Placement Options

In the second step, select **Countdown Timer** as the banner type to create a countdown timer for your Shopify store.

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*LO92vqm5pVkHDBgjGMrWLQ.png)

Select Countdown timer option

For the countdown type, you can choose from three options based on your promotional requirements:

1. **Till End Date**: Ideal for sale countdowns with specific start and end dates, such as Black Friday or seasonal sales.
2. **Recurring Countdown**: Perfect for weekly recurring promotions, where the countdown resets on selected days, such as Tuesday or weekend sales.
3. **Time Window**: Best suited for shipping deadline timers that reset daily, such as “ **Order within 4 hours for dispatch today.**”

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*5TaLURY4vT4qwSUolffX3w.png)

Types of countdowns

### Sale Countdown: Till End Date

With this option, the timer **counts down to the end date** specified by the user. For example, if you’re running a festival sale with 20% off that ends in five days, simply set the end date to five days from now.

The countdown timer displays the **remaining time until the sale ends**. Once the current date and time pass the configured end date, the **timer expires and is automatically hidden** from your storefront.

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*k67dn8DU1YSqOzyLYROUyQ.png)

Sale countdown till end date

To create an end-date-based countdown, navigate to the **Countdown Setup** tab and select **Till End Date** as the countdown type. Set your desired end date and save the banner to activate the countdown timer.

### Weekly Recurring day-based sale: Time Duration

This option lets you create an **evergreen countdown timer** that counts down from a specified duration and **automatically resets** when the countdown reaches zero.

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*CL4tcofh7EtjARNBzaIlEA.png)

Weekly recurring coundown

For example, suppose you want to offer discounts on selected products **every Tuesday and automatically repeat the promotion each week** without having to configure it again.

To achieve this, set the **Duration to 7 days** and the **Start Date to 12:00 AM on the previous Tuesday**. The countdown will run for seven days and automatically reset every Tuesday.

You can also restrict the countdown timer to display only on Tuesdays by adding the following code under **Custom Code → Custom JavaScript**:

```
// Function to check the UTC day and hide/show the banner form
function checkAndHideBannerForm() {
    const widgetId = "your-widget-id-here"; // Replace with your actual widget ID if dynamic
    const bannerForm = document.querySelector(`.profy-${widgetId}-banner-form`);

    if (!bannerForm) return; // Exit if the element doesn't exist on the page

    // getUTCDay() returns 0 for Sunday, 1 for Monday, 2 for Tuesday, etc.
    const currentUTCDay = new Date().getUTCDay();

    // If it is NOT Tuesday (2), hide the banner form
    if (currentUTCDay !== 2) {
        bannerForm.style.display = "none";
    } else {
        bannerForm.style.display = ""; // Reset or show if it is Tuesday
    }
}

checkAndHideBannerForm()
```

### **Shipping deadline timer: Specific hours of a day**

This option lets you display a countdown timer within a **specified time window each day**. The timer automatically resets daily, making it ideal for recurring promotions and shipping deadline notifications.

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*WqJmz-_HHbWsgu-DAGOqdA.png)

Time window countdown

For example, suppose you want to display a shipping deadline timer that promises **next-day delivery for orders placed before 2 PM**.

Set the **Time Window** between 12:00 AM (0 hours) and 2:00 PM (14 hours). Add a countdown message such as “ **Products will be delivered by tomorrow.**”

The timer will count down to 2 PM and automatically disappear once the deadline passes. It will then reset and appear again at midnight the following day, ready for the next day’s orders.

### 4) **Enter banner content**

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*2jxBXRJ1thsBtctF7CQgvw.png)

Basic details section

Based on your requirements, enter the appropriate **banner message and button text**, and configure the **destination URL** where customers should be redirected when they click the button.

### 5) Choose which pages to display on

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*cZss8tCttuWkon7cYxDkog.png)

Banner targeting options

By default, the **banner is displayed across all pages** of your Shopify store. However, you can customize the banner targeting to display it only on selected pages.

### **6) Customize countdown timer design base on your Store theme**

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*5x9sQpDb0RnRmcy7L3jg3A.png)

Timer Settings

Choose from **five unique countdown timer designs** and customize the **label, digit, and background colors** to match your store’s branding and style.

### 7) Configure banner visibility

In the **Visibility Settings** tab, you can configure the banner’s display position (top or bottom), enable the sticky banner option, and set its start and end dates. You can also customize additional visibility settings to control when and where the banner appears on your storefront.

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*gy0hW2-fc-Xa6W6OZXGOww.png)

Visibility settings

### 8) Final result

Once saved, the countdown timer banner will appear in your selected placement on the storefront, displaying the timer according to the countdown settings configured during banner setup.

Press enter or click to view image in full size

![](https://miro.medium.com/v2/resize:fit:700/1*_k_uBL9BOO8Xd_PZhbY2ww.png)

Final result
