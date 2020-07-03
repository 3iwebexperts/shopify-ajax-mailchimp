# shopify-ajax-mailchimp
shopify ajax mailchimp popup

Steps :

1. add mailchimp.js in assets
2. add popup.liquid as snippet
3. include popup snippet in theme.liquid
4. add mailchimp.js in theme.liquid in head , {{ 'mailchimp.js' | asset_url | script_tag }}
5. create required options in schema

mailchimp action URL STRUCTURE will be : https://3iwebexperts.us12.list-manage.com/subscribe/post-json?u=bf7ee457d0723e7714f7f6e43&amp;id=141f2e5a58&amp;c=?
