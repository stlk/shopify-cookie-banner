# Shopify cookie banner

Jak přidat cookie lištu do [Dawn](https://themes.shopify.com/themes/dawn/styles/default) šablony. V `layout/theme.liquid` udělejte následující změny.

1. Složky `assets` a `snippests` zkopírujte do vaší šablony.
2. Před `</body>` přidejte `{% render 'cookies' %}`.
3. Do `<head>` přidejte `{{ 'cookies.css' | asset_url | stylesheet_tag }}`.