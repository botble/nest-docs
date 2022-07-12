# Release Notes

- [Nest 1.5](#version_1_5)
- [Nest 1.4](#version_1_4)
- [Nest 1.3](#version_1_3)
- [Nest 1.2](#version_1_2)
- [Nest 1.1](#version_1_1)
- [Nest 1.0](#version_1_0)

<a name="version_1_5"></a>
## Nest 1.5
### Jul 13, 2022
- Add Stripe Checkout option. Enable it in Admin -> Payments -> Payment methods.
- Add option to download available translation files from GitHub.
- Move folder /resources/lang to /lang.
- Add order referrals (UTM tracking) https://prnt.sc/sft4o0m2noDJ
- Add permission to manage license.
- Add search settings (Admin -> Ecommerce -> Advanced settings).
- Fix multi-language in the vendor dashboard.
- Fix Arabic language (RTL language) in invoice.
- Fix media URL.
- Fix order history.
- Fix PayPal payment gateway.
- Fix product categories filter.
- Correct product quantity when placing order, cancel order.
- Fix RTL style.
- Prevent issue when deactivating plugin Language.
- Prevent order creation when payment failed.
- Improve payment process.
- Improve admin UI.
- Improve menu.
- Improve cache system (fix cache won't be cleared after translating data).
- Update libraries / third-party package to the latest version.
- Improve queries performance.

<a name="version_1_4"></a>
## Nest 1.4
### May 24, 2022
- Add custom HTML shortcode.
- Add text direction toolbar to editor.
- Add option to add custom HTML to header, body or footer of page.
- Add option to regenerate media thumbnails from admin panel.
- Add memory limit & max execution time info to system information page.
- Add option to add watermark for images in specific folders.
- Allow to redirect all 404 requests to homepage.
- Add DB index to some tables.
- Handle error when activating license.
- Fix image rotate issue when cropping thumbnails.
- Fix media download on PHP 8.
- Fix Admin RTL mode.
- Improve contact form: add math captcha, blacklist words & domains to prevent spam mails.
- Improve multi-language.
- Improve dashboard widgets style & pagination.
- Improve license system.
- Improve admin bar.
- Refactor code.
- Update libraries.
- Optimize queries.

<a name="version_1_3"></a>
## Nest 1.3
### Mar 22, 2022
- Notify vendor when creating order from the admin panel.
- Allow vendor to add product FAQ.
- Allow vendor to update shipping status.
- Add option to hide store phone number.
- Popular Products section on homepage.
- Fix gallery images for product variation.
- Fix product's price.
- Fix shipping address.
- Fix product images in vendor dashboard.
- Fix order creation.
- Fix order cancellation.
- Fix product name on invoice & reorder.
- Fix city form.
- Fix language advanced plugin.
- Fix plugin activation.
- Fix menu contains &amp;
- Improve shortcode [product-categories].
- Improve vendor dashboard.
- Improve plugin Location.
- Improve editor.
- Refactor code & improve queries.
- Update Laravel framework to 8.83.5.

<a name="version_1_2"></a>
## Nest 1.2
### Feb 19, 2022
- Add option to change city/state to dropdown. Check docs: [Location](usage-location.md).
- Fix product price on homepage blocks.
- Fix issue with Cloudflare SSL.
- Fix tree category & social links.
- Fix duplicate shortcode in CKEditor.
- Fix saving SEO meta tags.
- Update product import template.
- Improve invoice.
- Improve license.
- Improve permalink.
- Improve dashboard widgets.
- Improve core.
- Prevent Method Not Allowed error when use ajax DELETE/PUT.
- Add schema for post & page.
- Update AWS S3 settings.

<a name="version_1_1"></a>
## Nest 1.1
### Jan 16, 2022
- Fix product gallery images in quick view.
- Fix menu level 3, 4...
- Fix issue product price / SKU is not changed when selecting attributes.
- Fix issue with Cloudflare SSL.
- Fix tree category.
- Fix duplicate shortcode in CKEditor.
- Fix SEO title.
- Fix price filter on mobile.
- Fix issue when changing default language.
- Fix saving meta box data.
- Add option to hide out of stock products.
- Add option to disable sticky header.
- Add option to disable product image zoom (disable it in Admin -> Appearance -> Theme options -> tab Ecommerce).
- Add option to disable animation (Admin -> Appearance -> Theme options).
- Add FAQ shortcode.
- Add shipments list.
- Add export products to CSV.
- Add home 5 & home 6.
- Make FAQ section in product details page translatable.
- Improve invoice.
- Improve contact form.
- Improve permalinks.
- Improve contact form.
- Improve theme UI.
- Improve license.
- Improve multi-language.
- Improve product reviews.
- Improve custom CSS.
- Optimize CSS/JS to improve performance.
- Fully RTL support.

<a name="version_1_0"></a>
## Nest 1.0
### Dec 04, 2021
- Initial release version 1.0.
