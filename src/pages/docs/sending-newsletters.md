---
title: Sending newsletters.
description: Deliver newsletters directly ro your readers.
---

Paragraph provides tooling to send newsletters directly to your readers.

---

## Email newsletter delivery

Before you publish a post, you can optionally send it as a newsletter to your subscribers.

All email gets sent from the email address `your-publication-slug@newsletter.paragraph.xyz`.

When a reader replies to your email, it gets delivered to your personal email on your account. (If you've only connected your wallet to your account, please add your email address to receive replies!).

If you're publishing [in a community](/docs/creating-posts#communities), only users that subscribed to that community will receive your newsletter. (By default, when a user subscribes to your newsletter, they'll be subscribed to all communities).

If your community is [token-gated,](/docs/token-gated-content) your readers need to hold your required tokens in order to receive the newsletter. This is checked every time a newsletter is delivered (at delivery-time), ensuring that your readers truly hold the requiured tokens for access.

## Wallet newsletter delivery

We're actively working with the [XMTP team](https://xmtp.com) to deliver newsletters entirely on-chain via the XMTP protocol - no email needed.

Until this is launched, we require email for newsletter delivery.

## Managing subscribers

On your Paragraph [subscriber settings](https://paragraph.xyz/app/subscribers), you can view or remove your subscribers. You can also add new subscribers manually.

### Importing subscribers

You can also import subscribers via CSV. This is helpful if you already have a Substack or Revue email list export.

Visit your Paragraph [import/export settings](https://paragraph.xyz/settings/publication/import-export), and click `Import subscribers`. Your CSV file should have an `email` column, and optionally a `created_at` column.

## Email signup forms

You can link to or embed an email signup form on your own personal website.

Link directly to your signup form by appending `/subscribe` to your newsletter (ie, https://paragraph.xyz/@blog/subscribe).

Embed the signup form into another website by using an iframe. Copy the embed code in your [publication settings](https://paragraph.xyz/settings/publication/blog) and paste the HTML elsewhere.
