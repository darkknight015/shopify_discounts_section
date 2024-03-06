# Product Discount Timer

This repository contains code for creating a discounts timer section in shopify.
Total 2 files are used which in which first one is liquid file responsible for creating "section" and other is responsible for the css of the discounts section. 

In section, you can set heading and short description, select product to show, add timer (date must be in this format 2024-03-08 23:54:00), notation for discount and add percentage for discount.

In discounted-product.liquid file, the code is responsible for creating a section in which Product can be selected to show dynamically in the section while the timer can be setup which countdowns to 0. Once the timer becomes 0 or less, the discounts section automatically disappears.

**The discounted-product.liquid file can be uploaded in your Shopify Theme > Edit Code > Sections and its JS code is also added inside the section. While the css file can be included in theme.liquid.**

It should be compatible with all the themes since its general code, otherwise you can raise issues as well.

**Use this code in header for including css file =>** {{ 'dk_custom_style.css' | asset_url | stylesheet_tag }}

**Use below code in header to include google fonts used by the discount section**

<link rel="canonical" href="{{ canonical_url }}">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inder&family=Inter:wght@100..900&display=swap" rel="stylesheet">

**The sweetest thing about this section is, you can add as many section with different timers as you want on same page**

Thanks & Regards
**Darkknight**
