# WooCommerce Price Dropdown Plugin

Display your store prices in the visitor’s local currency automatically.

This free WooCommerce plugin detects the visitor’s country via IP, converts all prices in real time using up-to-date exchange rates, and provides a clean searchable currency dropdown so customers can switch currencies manually if they prefer.

---

## Key Features

- Automatic country detection based on visitor IP
- Real-time price conversion across the entire store
- Support for 193 countries and 155+ currencies
- Searchable currency dropdown with flags and currency codes
- Converts product prices, variations, shipping rates, and coupon amounts
- Remembers the selected currency for 30 days
- Mobile-friendly bottom sheet design
- Saves currency details with every order
- Simple admin settings under WooCommerce
- Handles zero-decimal currencies correctly (JPY, KRW, etc.)

---

## Download

**Current release: v1.0.0**

[Download the plugin ZIP](https://github.com/CodeKumaCom/woocommerce-price-dropdown-plugin/releases/latest/download/woocommerce-price-dropdown-plugin-v1.0.0.zip)

All versions are available on the [Releases page](https://github.com/CodeKumaCom/woocommerce-price-dropdown-plugin/releases).

---

## Installation

1. Download the ZIP file.
2. In WordPress go to **Plugins → Add New → Upload Plugin**.
3. Select the ZIP and click **Install Now**.
4. Activate the plugin.

After activation, go to **WooCommerce → Multi-Currency** to review settings and exchange rates.

---

## Adding the Currency Selector

Use the shortcode anywhere on your site:

[price_dropdown]


Optional attributes:

- `show_flag="yes"` or `"no"`
- `show_currency="yes"` or `"no"`
- `placeholder="Select Country"`

You can also place it in a widget area or use `do_shortcode()` in your theme templates.

---

## How It Works

1. On the first visit the plugin detects the visitor’s country from their IP address.
2. It sets the matching currency and converts all prices using the latest exchange rates.
3. The visitor can change currency at any time using the dropdown.
4. The chosen currency is remembered for 30 days via session and a secure cookie.
5. Every order stores the exact currency, symbol, and exchange rate used at checkout.

---

## Settings

Located under **WooCommerce → Multi-Currency**:

- Optional IP geolocation token
- Enable / disable automatic country detection
- Exchange rate refresh interval (6, 12, or 24 hours)
- Manual “Refresh Rates” button
- Full table of current exchange rates

---

## Requirements

- WordPress 5.8+
- WooCommerce 6.0+
- PHP 7.4+

---

## License

Distributed under the GPL-2.0-or-later license.
