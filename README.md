# We Built This Compass to Outlast Us

The Truest North Compass is designed to be a modern heirloom—something you can pass down to your kids. That means it needs to keep working long after the latest apps have been abandoned and today's wireless protocols have been replaced by something new.

So we made a decision: **no apps, no Bluetooth, no accounts, no servers required.**

Your compass works offline, forever. And if Truest North Compass ever goes away (like so many IoT companies do), you'll still be able to reprogram your compass yourself. That's why we've open-sourced the reprogramming tool right here.

---

## How to Reprogram Your Compass

**Option 1: Use our website (easiest)**

Go to [reprogram.truestnorthcompass.com](https://reprogram.truestnorthcompass.com) and follow the instructions. That's it.

**Option 2: Use the file in this repository**

If our website ever disappears, you can open [`reprogram.html`](./reprogram.html) directly in any web browser. It works offline—no internet connection needed. Just download it and keep a copy somewhere safe.

---

## What is StrobeCode?

StrobeCode is what we call our screen-flash reprogramming system. Here's how it works:

1. You enter coordinates on your phone or tablet
2. Your screen flashes a pattern of black and white
3. The compass reads the flashes through its light sensor
4. Done. New destination programmed.

**It takes about 10 seconds.** No app to install. No pairing. No account to create. Any screen that can display a webpage can reprogram your compass—your phone today, whatever replaces phones tomorrow.

We designed it this way on purpose. Bluetooth protocols change. Apps get abandoned. But screens and light? Those aren't going anywhere.

---

## What's in This Repository

| File | What It Is |
|------|------------|
| `reprogram.html` | The complete reprogramming tool. Works offline in any browser. |
| `compass user manual.pdf` | Printed manual that ships with the compass. |

---

## For the Technically Curious

The reprogramming interface converts GPS coordinates into binary data and transmits it via precise screen flash timing. The compass's light sensor reads these flashes and stores the coordinates in non-volatile memory.

- Single destination or sequences of up to 10 locations
- Works on any modern browser (mobile or desktop)
- No server communication—everything runs locally
- MIT licensed, so fork it, modify it, do whatever you want

---

## Why We Did This

We've seen too many "smart" products become paperweights when the company behind them shuts down or decides to stop supporting them. We didn't want that for something people are giving as wedding gifts and proposal keepsakes.

If you bought a Truest North Compass, it's yours. Really yours. Not "yours as long as we keep the servers running." We think that's how it should be.

---

## Questions?

- **Compass not responding to flashes?** Make sure your screen brightness is at 100% and the compass is face-down on the screen.
- **Something else?** Email us at info@truestnorthcompass.com or visit [truestnorthcompass.com/contact](https://truestnorthcompass.com/pages/contact)

---

*Made with care in Buffalo, NY.*
