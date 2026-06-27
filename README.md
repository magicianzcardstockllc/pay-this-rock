# Pay This Rock

Mobile-first landing page for an NFC-tagged rock.

## Payment flow

NFC tag → `https://paythisrock.com` → Pay This Rock button → Buy Me a Coffee → Stripe payout to MagicianzCardstock LLC.

The payment button currently points to:

`https://buymeacoffee.com/magicianzcardstock`

## Publish on GitHub Pages

1. Upload `index.html` to the root of the public `pay-this-rock` repository.
2. In repository Settings → Pages, deploy from `main` and `/(root)`.
3. Set the custom domain to `paythisrock.com`.
4. Complete the required DNS records with the domain registrar.
5. Enable HTTPS after GitHub verifies the domain.

## Before attaching the NFC tag

1. Confirm `https://paythisrock.com` opens correctly.
2. Confirm the Pay This Rock button opens the Buy Me a Coffee page.
3. Confirm Stripe payout status is active before accepting payments.
4. Program the NFC tag with `https://paythisrock.com`.
