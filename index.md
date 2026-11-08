# Maison Editorial — Theme Documentation

Maison Editorial is an Online Store 2.0 Shopify theme designed for editorial-style luxury fashion storefronts, including apparel, footwear, handbags, jewellery, watches and accessories.

**Theme version:** 0.3.0  
**Developer:** Ecommark Digital  
**Support:** [Contact the support team](/maison-editorial-documentation/support/)

> This documentation describes the current theme build. Some features depend on Shopify store configuration, product data, installed apps and the active theme settings. Always test changes in an unpublished theme before publishing to a live storefront.

## Contents

- [Getting started](#getting-started)
- [Installing the theme](#installing-the-theme)
- [Customizing the storefront](#customizing-the-storefront)
- [Homepage sections](#homepage-sections)
- [Products and variants](#products-and-variants)
- [Collections and search](#collections-and-search)
- [Cart and checkout](#cart-and-checkout)
- [Navigation, header and footer](#navigation-header-and-footer)
- [Localization and social links](#localization-and-social-links)
- [Apps and custom Liquid](#apps-and-custom-liquid)
- [Images and performance](#images-and-performance)
- [Troubleshooting](#troubleshooting)
- [Support](#support)

## Getting started

Before configuring the theme:

1. Sign in to your Shopify admin.
2. Add products, product images, prices, variants and inventory.
3. Create collections and assign products to them.
4. Create the pages, blog content and menus your storefront needs.
5. Configure shipping, taxes, payments, markets and checkout in Shopify admin.
6. Add the theme to your development or unpublished themes and customize it before publishing.

The theme does not create products, collections, policies, menus, payment settings or shipping rates for you.

## Installing the theme

For a theme ZIP:

1. In Shopify admin, go to **Online Store → Themes**.
2. In the Theme library, choose **Add theme → Upload zip file**.
3. Select the theme ZIP and wait for Shopify to finish uploading.
4. Choose **Customize** to configure the unpublished copy.
5. Preview and test the storefront before publishing.

For development work using Shopify CLI, use the official Shopify CLI theme development and deployment documentation: https://shopify.dev/docs/api/shopify-cli/theme

## Customizing the storefront

1. In Shopify admin, go to **Online Store → Themes**.
2. Find Maison Editorial and select **Customize**.
3. Use the page selector at the top of the theme editor to switch between the homepage, product, collection, cart and other templates.
4. Select a section to edit its available settings and blocks.
5. Use **Add section** to add supported sections to the current template.
6. Save changes and preview the storefront on desktop and mobile.

Available settings depend on the section and template. The theme editor controls presentation; product, collection, inventory, market and checkout data remain managed in Shopify admin.

## Homepage sections

The homepage template supports editorial merchandising sections such as:

- Editorial hero and slideshow banners
- Featured collection and featured product
- Image with text and image gallery
- Rich text and multicolumn content
- Logo list and testimonials
- Newsletter signup and blog posts

For a polished result, use consistent image proportions, concise headings and clear calls to action. Avoid placing too many competing hero banners or promotional sections on the same page.

## Products and variants

The product template supports product media, variant selection, price and compare-at price, availability, quantity, product descriptions, SKU, selling plans where configured, accelerated checkout where available, app blocks, and custom Liquid blocks.

To configure a product:

1. Go to **Products** in Shopify admin.
2. Add or open a product.
3. Add a clear product title, description, price and high-quality media.
4. Configure options and variants (for example size or colour).
5. Set inventory and shipping details.
6. Save, then preview the product page using the theme editor.

Variant availability and purchase options depend on the product's Shopify configuration. Subscription or selling-plan features require a compatible selling-plan setup or app. Pickup availability appears only when local pickup is configured and the product is eligible.

## Collections and search

Create collections in **Products → Collections**. Add products manually or define automated collection conditions. The collection template includes product listing, sorting, filtering where supported by the store's Shopify configuration, and pagination.

Search results are generated from Shopify storefront search. Product visibility and search behavior can depend on sales-channel publication, product status and Shopify search settings.

## Cart and checkout

The cart supports quantity changes, line-item discounts, cart discounts, cart notes, selling-plan details, item properties and accelerated checkout buttons where available.

Payment methods, shipping rates, taxes, discounts, checkout language and payment processing are configured in Shopify admin—not in the theme. Test the complete cart-to-checkout flow using Shopify's supported test payment methods before launch.

## Navigation, header and footer

Create menus in **Content → Menus** (or **Online Store → Navigation**, depending on the Shopify admin interface). Assign the appropriate menu in the theme editor's header or footer settings.

Use concise menu labels and a shallow hierarchy. Dropdown navigation should be tested with keyboard, mouse and touch input.

## Localization and social links

Configure supported markets, languages and currencies in Shopify admin. The theme displays localization selectors when multiple eligible country/region or language options are available.

Add social profile URLs in the theme settings for the social platforms provided. Leave a field blank if the brand does not have an active profile.

## Apps and custom Liquid

Where a section exposes an app block, compatible Shopify apps can add their supported storefront content through the theme editor. The custom Liquid section/block is intended for merchant-managed Liquid and HTML snippets.

Only add code from sources you trust. Custom code and third-party apps can affect storefront performance, accessibility, security and compatibility. Back up the theme and test changes in an unpublished copy first.

## Images and performance

Use sharp, appropriately sized product and editorial images. Keep image subjects and focal points visible on mobile as well as desktop. Avoid uploading unnecessarily large source images.

Performance depends on image weight, app scripts, custom code, product count, third-party services and merchant content—not just the theme. After customization, test representative homepage, product and collection pages on mobile and desktop using Lighthouse or PageSpeed Insights.

## Troubleshooting

**A section or setting is not visible:** Confirm you are editing the correct page template and that the section has been added to that template.

**A product option cannot be purchased:** Check that the variant exists, is active, is available on the Online Store sales channel and has the correct inventory or continue-selling policy.

**Pickup availability is missing:** Confirm local pickup is enabled for an eligible location and the product variant is available there.

**A localization selector is missing:** Check that more than one eligible market/country or language is configured and published.

**An app block is unavailable:** Confirm the app supports Online Store theme app extensions and that its app embed or block is enabled as required by the app provider.

**The storefront looks different on mobile:** Review image focal points, section settings, long headings and custom code at mobile widths. Test on an actual device where possible.

## Frequently asked questions

**Can I use Maison Editorial for a store outside the fashion industry?**  
Yes. The theme is designed around editorial merchandising and can be configured for other product-led brands, although its default art direction is optimized for fashion, accessories and lifestyle products.

**Why is my hero or featured collection empty after installation?**  
The theme does not bundle a merchant's campaign images, products or collections. Select a hero image and assign a collection in the Theme Editor.

**Why are product filters or recommendations not appearing?**  
Shopify only displays filters and recommendations when the store has the relevant product data, Search & Discovery configuration and eligible products. Confirm those settings in Shopify admin.

**Why is the Follow on Shop button not visible?**  
The Shop channel and Shop Pay must be available and enabled for the store. Shopify controls the branded button and its availability.

**Can I edit theme code?**  
Yes, but duplicate the theme before editing code. Custom code can affect updates, accessibility, performance and compatibility. Use a qualified Shopify developer if you are unsure.

## Support policy

For theme setup questions or to report a theme issue, use the [Maison Editorial support contact form](/maison-editorial-documentation/support/). You can also email [khingsmhart45@gmail.com](mailto:khingsmhart45@gmail.com) if the form is unavailable.

We aim to acknowledge theme support requests within two business days. Critical storefront defects are prioritized for investigation and correction. Support covers installation guidance, theme settings, and defects in the theme's shipped functionality. Custom development and third-party app configuration are outside standard theme support.

When reporting an issue, include the affected page URL, a description of the expected and actual behavior, the device/browser, and steps to reproduce it. Screenshots are helpful. Do not send passwords, payment details or other sensitive account information.

The support form accepts issue details and one optional file attachment. An automatic acknowledgement is configured. The first submission must be used to activate the FormSubmit.co endpoint by confirming the activation email sent to the support inbox. Test the form after activation before Theme Store submission.

## Useful Shopify resources

- Shopify themes: https://help.shopify.com/en/manual/online-store/themes
- Customize your theme: https://help.shopify.com/en/manual/online-store/themes/customizing-themes
- Shopify theme editor: https://help.shopify.com/en/manual/online-store/themes/theme-structure
- Shopify CLI theme commands: https://shopify.dev/docs/api/shopify-cli/theme
