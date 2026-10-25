# 🧮 Break-Even ROAS & CPA Calculator (2026 Edition)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/cash602-cmd/roas-calculator)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Powered by KuajingBase](https://img.shields.io/badge/Powered%20by-KuajingBase-6366f1.svg)](https://kuajingbase.com/en)

A lightweight, zero-dependency, browser-based unit economics calculator for cross-border e-commerce sellers, media buyers, and DTC store operators.

👉 **Live Tool:** [https://roas-calculator-free.netlify.app](https://roas-calculator-free.netlify.app)  
👉 **Full 38-in-1 Suite:** [KuajingBase Cross-Border Toolkit](https://kuajingbase.com/en/toolkit)

---

## 🎯 Why We Built This

Over 80% of newly launched independent stores fail not because of product defects or poor ad copy, but due to **miscalculating the unit break-even floor**. When media buyers scale ad budgets based solely on blended ROAS reported by Meta or TikTok Ads Manager, unexpected shipping surcharges, gateway transaction fees, and COGS silently deplete operating cash flow.

This micro-tool computes your **exact break-even ROAS** and **maximum acquisition cost (CPA)** in real time before scaling campaigns.

---

## 📐 Mathematical Formulation

### 1. Unit Gross Margin
$$\\text{Gross Profit} = \\text{Selling Price} - \\text{COGS} - \\text{Shipping \\& Packaging}$$

### 2. Break-Even ROAS
$$\\text{Break-Even ROAS} = \\frac{\\text{Selling Price}}{\\text{Gross Profit}}$$

*If gross profit is $\\le 0$, the calculator actively issues a negative margin warning, as advertising is financially inviable.*

### 3. Estimated Net Margin
$$\\text{Net Profit Margin} = \\frac{\\text{Gross Profit} - \\text{Ad Spend Per Order}}{\\text{Selling Price}} \\times 100\\%$$

---

## 🚀 One-Click Netlify Deployment

1. Fork or clone this repository.
2. Log into [Netlify](https://app.netlify.com).
3. Click **Add new site** > **Import an existing project** > **GitHub**.
4. Select `roas-calculator`.
5. Deploy settings:
   - **Publish directory:** `.` (root)
   - **Build command:** (leave empty)
6. Click **Deploy**. Your custom high-performance edge tool will be live in 10 seconds.

---

## 📚 Related Resources & Guides

Maintained by the engineering and cross-border research team at [KuajingBase](https://kuajingbase.com/en):

- [Cross-Border Profit & Fee Modeling Suite](https://kuajingbase.com/en/toolkit/profit-calculator) — Advanced margin calculation with returns, refunds, and multi-tier pricing.
- [Cross-Border Payment Gateway Comparison Hub](https://kuajingbase.com/en/payment) — Real currency conversion spreads and processing fee audits across Stripe, PayPal, and Airwallex.
- [DTC Independent Store Launch & Scaling Guide](https://kuajingbase.com/en/guide) — Step-by-step technical architecture for WooCommerce and Shopify.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.