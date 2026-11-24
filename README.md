# ai-chat-exporter-site
Landing page and privacy policy for AI Chat Exporter, hosted on GitHub Pages.

- Landing page: https://www.r69shabh.me/ai-chat-exporter-site/
- Privacy policy: https://www.r69shabh.me/ai-chat-exporter-site/privacy-policy.html

No build step. To preview from the repository root, run `python3 -m http.server 8000`. For deployment, enable GitHub Pages with **Deploy from a branch → main → / (root)** after merging the site.

## Launch links

All three placeholders are in the downloads section of `index.html`. Each link is disabled until its destination is available. To activate one, add its `href` and remove `aria-disabled` and `role`; update the launch note once the links are available.

| Link ID | Destination |
| --- | --- |
| `edge-addon` | Published Microsoft Edge Add-ons listing |
| `firefox-addon` | Published Firefox Add-ons (AMO) listing |
| `gumroad-pro` | Published Gumroad product URL (the extension’s `GUMROAD_PRODUCT_URL` is also empty until launch) |
