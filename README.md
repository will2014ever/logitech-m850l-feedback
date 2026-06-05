# Logitech M850L & M840L — Live User Feedback Tracker

A live-updating dashboard tracking user and media feedback for the Logitech Signature Comfort Plus M850L and M840L mice across global e-commerce and review platforms.

**Live site:** https://will2014ever.github.io/logitech-m850l-feedback/

## Coverage

| Platform | Region |
|---|---|
| Amazon US/CA/UK | Global |
| JD.com (京东) | China |
| Taobao/Tmall | China |
| 什么值得买 (smzdm.com) | China |
| 知乎 (Zhihu) | China |
| Reddit (r/MouseReview, r/logitech) | Global |
| YouTube | Global |
| Bilibili | China |
| Press media (The Register, GearBrain, MobileSyrup, IT之家) | Global |

## Update Schedule

Updated **every Friday** via the `product-feedback-monitor` Claude Code skill.

## How updates work

1. The monitoring skill searches all platforms for new reviews
2. `data.json` is updated with new entries
3. Changes are committed and pushed — the site auto-reflects the new data
4. `index.html` fetches `data.json` at load time (no rebuild required)

## Products

- **M850L** — Signature Comfort Plus, $49.99, with soft palm cushion (Logitech-first)
- **M840L** — Signature Comfort, $39.99, without cushion

Announced: May 26, 2026 | Shipping: June 2026
