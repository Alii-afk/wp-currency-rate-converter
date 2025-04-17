# 💱 WordPress Currency Converter Plugin

A lightweight and flexible WordPress plugin that allows site admins to define currency exchange rates via the dashboard, and display a live conversion widget on the frontend using a simple shortcode.

---

## ✨ Features

- Add and manage custom currencies from the WordPress admin
- Set exchange rates manually (ideal for fixed or non-standard rates)
- Use `[crc_currency_exchange_shortcode]` to embed a currency converter anywhere
- Mobile-friendly and minimal frontend display
- No external API dependency

---

## 🛠️ Installation

1. Upload the plugin to your WordPress site:
   - via `Plugins → Add New → Upload Plugin`
   - or extract and place in `/wp-content/plugins/`
2. Activate the plugin
3. Go to **Settings → Currency Converter** to add exchange rates

---

## 🔧 Shortcode Usage

Place the shortcode below on any page or post:

```php
[crc_currency_exchange_shortcode]
