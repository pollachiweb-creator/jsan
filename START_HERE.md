# TourGo website source package

Start with `docs/SETUP_AND_UPLOAD.md` for installation and `docs/CONTENT_PORTAL_GUIDE.md` for everyday use.

## Included

- Complete React/Vinext website source, original photos, styles and dependency lockfile.
- 32 sample experience pages, 12 destination landing pages and 7 category pages.
- Direct page navigation, search, cart and demonstration checkout.
- Secure ChatGPT sign-in on the hosted edition, plus an email-code activation flow.
- Server-stored account and supplier profiles, tour submissions and owner approvals.
- Immediate rejection of detected spam, submission limits and account blocking.
- Aggregate public-page view reports for the administrator.
- D1 database schema, migration and isolated security integration tests.

## What still requires configuration

Verification email delivery requires `RESEND_API_KEY` and `VERIFICATION_FROM_EMAIL` from your own verified email service. No real code has been sent or inbox delivery tested. Until connected, accounts stay inactive and cannot submit tours. The verification secret and owner admin allowlist are configured separately in the hosted environment, not included in this download.

This hosted edition uses ChatGPT sign-in first. It is not independent email-only authentication. Moving to another host requires a secure identity adapter and compatible database hosting.

Cart, bookings, vouchers, reviews and payments are demonstrations. There is no payment gateway, live supplier inventory connection, production booking engine, custom photo upload or CSV import. Original sample tours are not automatically verified commercial inventory. Spam rules reduce abuse but cannot detect every kind of spam.

No live credentials, customer records, verification codes or database exports are included.
