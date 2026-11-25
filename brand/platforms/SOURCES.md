# Platform logo sources

Official vendor assets, stored locally so the site never hotlinks a third-party
CDN. Each file is used unmodified apart from trimming surrounding canvas
whitespace in the `viewBox`; artwork, colours and proportions are untouched.

| File                   | Platform                   | Source                                                                                                                           | Retrieved  |
| ---------------------- | -------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| `magento.svg`          | Magento Open Source        | `raw.githubusercontent.com/magento/magento2/2.4-develop/lib/web/images/logo.svg` (official open-source Magento 2 repository)     | 2026-11-25 |
| `adobe-commerce.svg`   | Adobe Commerce             | `adobe.com/content/dam/cc/icons/Adobe_Corporate_Horizontal_Red_HEX.svg` (Adobe corporate mark, `#fa0f00`)                        | 2026-11-25 |
| `shopify.svg`          | Shopify / Shopify Plus     | `shopify-assets.shopifycdn.com/shopifycloud/brochure/assets/brand-assets/shopify-logo-primary-logo-*.svg` (Shopify brand assets) | 2026-11-25 |
| `shopify-white.svg`    | Shopify (dark backgrounds) | Shopify brand assets, monotone white variant                                                                                     | 2026-11-25 |
| `bigcommerce.svg`      | BigCommerce                | `dam.bigcommerce.com/m/11748382b20ebf3e/original/BigCommerce-logo-all-10.zip` → `BigCommerce-logo-dark.svg`                      | 2026-11-25 |
| `bigcommerce-mark.svg` | BigCommerce (logomark)     | `dam.bigcommerce.com/m/5158e7a0ce62edbf/original/BigCommerce-logomark-all-6.zip` → `BigCommerce-logomark-whitebg.svg`            | 2026-11-25 |

## Usage notes

- 9Colon is a **BigCommerce Technology Partner** and a **Shopify Technology
  Partner**, so partner marks may be displayed. An Adobe Community Partner
  relationship is pending and is **not** claimed anywhere on the site.
- Magento Open Source is open source; its mark is used to identify the platform.
- The Adobe corporate mark identifies Adobe Commerce as an Adobe product. No
  Adobe partnership, certification or endorsement is implied.
- Logos are always rendered at their intrinsic aspect ratio inside a light
  plate, so brand colours are never recoloured, stretched or distorted and the
  marks stay legible in both themes.
- Do not add a logo for a platform without an approved asset. Adobe Edge
  Delivery Services, Commerce Optimizer and App Builder have no standalone
  approved marks, so they use neutral technical icons.
- Replace a file here and every consumer updates automatically; no component
  hardcodes an asset path outside `components/ui/platform-logo.tsx`.
