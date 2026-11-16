# Awesome-Geo-Location-Price-Localization

# Top Geo-Location & Price Localization Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Market-Specific Pricing, Currency Localization & Self-Hosted Personalization Engines*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Geo-Location & Price Localization**. These tools help businesses adapt pricing and content to local markets—covering everything from billing platforms that handle multi-currency subscriptions to personalization engines that adjust offers based on visitor location, and price optimization suites that model regional willingness-to-pay.

**Examples** include Chargebee, Dynamic Yield, Pricefx, PROS, Vendavo, Bloomreach, and open-source alternatives like Omniconvert Explore (free tier) (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted pricing analytics, open-source A/B testing with geo-targeting, and community-driven personalization—ideal for organizations seeking data sovereignty and avoiding per-traffic or per-domain SaaS pricing. The open-source landscape is genuinely thin for **full price optimization** (which requires proprietary data models and elasticity engines), but functional for **A/B testing and basic geo-personalization**: **Omniconvert Explore** offers a free tier with unlimited tests for up to 50,000 tested visitors, including geo-targeting and personalization features [citation:10].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Chargebee](https://www.chargebee.com/)** | **Billing platform with native multi-currency and market-specific pricing.** Configure prices in local currencies with **fixed or real-time exchange rates**; adapt plans by region without rebuilding your catalog. **Smart Routing Rules** pick the best payment gateway per currency. Tax (GST, Sales Tax, EU-VAT) calculated automatically based on customer location [citation:1][citation:11]. | Quote-only (Billing plans from ~$0 + % of invoicing) | No free tier for multi-currency; trial available |
| **[Dynamic Yield](https://www.dynamicyield.com/)** | **Real-time personalization and A/B testing engine.** Personalizes content, banners, and offers based on **geo, weather, device, and behavioral targeting** [citation:2]. Starting price reported at **$35,000/year**; reviews note the interface can feel overwhelming and A/B test reporting is somewhat limited [citation:12]. | From **~$35,000/year** [citation:12] | No free tier; demo via sales |
| **[Pricefx](https://www.pricefx.com/)** | **Modular pricing optimization suite.** **Plan package is subscription-free**—no recurring payments for analytics. **Price** adds price list management and optimization across segments; **Profit** adds CPQ, rebates, and deal planning [citation:3][citation:13]. | **Plan: Free** (analytics); Price/Profit: quote-only | **Free (Plan)**: pricing analytics with no time limit [citation:13] |
| **[PROS Smart CPQ](https://www.pros.com/)** | **AI-driven CPQ and dynamic pricing for global teams.** **Converted Price Widget** shows real-time currency conversions in a single quote column—no separate columns per currency. **Multi-language template support** for localized documents. Supports global currencies and localization [citation:4][citation:14]. | Quote-only (private offers via Microsoft Marketplace) | No free tier; demo via sales |
| **[Vendavo](https://www.vendavo.com/)** | **Price management for B2B across lines of business, regions, and channels.** Supports value-based and competitive pricing strategies; centralized system for diverse geographies and business models [citation:5]. | Quote-only | No free tier; demo via sales |
| **[Zilliant](https://www.zilliant.com/)** | **B2B price optimization with AI-driven guidance.** Price IQ engine, scenario modeling, and constraint-based optimization; integrates with ERP, CRM, CPQ, and eCommerce for consistent pricing across channels [citation:6]. | Quote-only | No free tier; demo via sales |
| **[Bloomreach](https://www.bloomreach.com/)** | **Personalization and product data platform with context-aware catalogs.** **Contexts in Data hub** (Oct 2026) let you tailor product data, prices, and availability per store, region, or price list from one catalog—ideal for location-based pricing [citation:7]. | Quote-only | No free tier; demo via sales |
| **[Monetate](https://www.monetate.com/)** | Personalization platform with geo and behavioral targeting. Gartner Peer Insights notes **custom-quote pricing** based on traffic volume, domains, and feature set [citation:9]. | Quote-only (custom by traffic/domains) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Omniconvert Explore](https://www.omniconvert.com/pricing/)** | — | **The most accessible free-tier option for geo-targeted A/B testing and personalization.** **Free plan includes unlimited A/B/n tests for up to 50,000 tested visitors**—not a stripped-down demo, but the full Explore feature set [citation:10]. **Geo-targeting** built in (country, region, IP, ISP), plus **weather conditions targeting**, RFM segments, and behavioral triggers. **Personalization features**: dynamic text replacement, on-exit/on-scroll overlays, and multi-device campaigns. **Trade-off**: not a price optimization engine—you define the pricing variations and Omniconvert serves them based on visitor context. **Best for teams wanting to test localized pricing and offers** without a commercial personalization contract [citation:10]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| ***(No mature open-source price optimization engines identified)*** | — | The search results did not surface any open-source projects comparable to Pricefx, PROS, Vendavo, or Zilliant. **Full price optimization requires proprietary elasticity models and customer data** that open-source projects have not replicated. Teams needing optimization should either use commercial platforms or build custom models on top of open data. |

**Frameworks for building custom systems**: The open-source path to geo-price localization is **A/B testing with geo-targeting, not optimization**. **Omniconvert Explore** provides a free tier with unlimited tests for up to 50k visitors, including geo, weather, and behavioral targeting [citation:10]. For **billing-side localization**, **Chargebee** handles multi-currency and tax automatically [citation:1][citation:11]. **No open-source project matches the elasticity modeling of Pricefx or Zilliant**—those require commercial platforms or custom data science.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Geo-location and price localization tools handle customer location data and pricing decisions; enforce privacy compliance (GDPR, CCPA) for geo-tracking and avoid discriminatory pricing practices that may violate consumer protection laws.
- **Price localization has two distinct layers that are often conflated.** **Billing localization** (Chargebee) handles currency conversion, payment routing, and tax—it does not optimize *how much* you charge in each market [citation:1][citation:11]. **Price optimization** (Pricefx, PROS, Zilliant) models willingness-to-pay and margin trade-offs—this is where the real revenue impact lives, but it requires proprietary data models and is almost exclusively commercial [citation:3][citation:4][citation:6]. **Dynamic Yield and Omniconvert** sit in between—they can serve different prices or offers based on geo, but the pricing strategy itself is defined by you [citation:2][citation:10]. **Open-source is genuinely thin here**: Omniconvert Explore's free tier is the most accessible way to test geo-targeted offers [citation:10], but **no open-source project replicates Pricefx's or Zilliant's optimization engines**. Validate whether you need billing localization (Chargebee), A/B testing (Omniconvert), or optimization (Pricefx/Zilliant) before committing.

---

**Made for pricing managers, revenue operations teams, and developers building localization infrastructure.**  
Let's make geo-location and price localization more open, transparent, and market-aware.
