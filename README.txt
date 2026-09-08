BEYOND BEER – VERBRAUCHSMATERIAL

This package is a standalone static PWA. It does not require Netlify, Resend,
Netlify Agent, or an API key.

Included:
- all 19 existing products and their existing stock/minimum/order data
- product search, low-stock filter, cart and barcode scanner
- local persistence on each device
- Unicode-safe PDF generation (German umlauts and ß render correctly)
- native share flow on iPad/iPhone/Android; Outlook can be selected and the PDF
  is attached directly when the device/browser supports file sharing
- desktop fallback downloads the PDF and opens the default mail client

Important:
A static website cannot silently send an email from a browser without a mail
provider/backend. On iPad the native share sheet can hand the PDF directly to
Outlook. For fully automatic server-side email delivery, connect the site to a
mail backend/provider later.
