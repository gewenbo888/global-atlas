# Global Atlas — 寰宇图志

Bilingual comparative atlas of eight world entities across seven dimensions.

[![Live Demo](https://img.shields.io/badge/demo-global--atlas.vercel.app-8b1a1a)](https://global-atlas-lake.vercel.app)

## Overview

A bilingual (English / Chinese) single-page site that places eight great units of humanity side by side:

1. **United States** — 美国
2. **European Union** — 欧盟
3. **China** — 中国
4. **ASEAN** — 东盟
5. **Brazil** — 巴西
6. **Russia** — 俄罗斯
7. **India** — 印度
8. **Africa** — 非洲

Each is measured across seven dimensions with indexed 0–100 scoring plus raw figures:

1. **Economy** — 经济 (nominal GDP, PPP GDP, trade share, FDI, financial depth)
2. **Administration** — 行政 (government effectiveness, rule of law, digital services)
3. **Politics** — 政治 (regime type, rights, liberties, geopolitical weight)
4. **Technology** — 科技 (R&D intensity, patents, unicorns, chips, AI, internet)
5. **Lifestyle** — 生活 (life expectancy, work hours, housing, pollution, leisure)
6. **Consumption** — 消费 (household spend, retail, e-commerce, brand density)
7. **Purchasing Power** — 购买力 (PPP per capita, cost of living, Big Mac index)

A comparative matrix of 10 core indicators lets readers scan every entity at once.

## Design & Tech

- **Stack:** Single HTML file, vanilla JavaScript, SVG compass, animated bar charts
- **Aesthetic:** Editorial atlas / almanac on cream parchment with rouge and gold accents
- **Color Coding:** Per-entity accents (US navy, EU blue, CN rouge, ASEAN sage, BR green, RU deep red, IN amber, AF gold)
- **Typography:** Fraunces (variable serif, English) + Noto Serif SC (Chinese) + JetBrains Mono (data)
- **Bilingual:** Live EN / 中文 toggle rewrites the page without reload
- **Deployment:** Vercel

## Links

- [Live Site](https://global-atlas-lake.vercel.app)
- [GitHub Repository](https://github.com/gewenbo888/global-atlas)
