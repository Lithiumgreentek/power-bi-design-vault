![preview](https://raw.githubusercontent.com/Lithiumgreentek/power-bi-design-vault/main/preview.svg)

# Power-Narrative Design Studio: Curated Visual Intelligence Resources for Modern Analysts

Welcome to the **Power-Narrative Design Studio** — a meticulously organized repository of Power BI dashboards, design pattern libraries, curated datasets, and visualization frameworks. This is not a product but a living laboratory for analysts, designers, and business intelligence architects who want to move beyond generic charts and into the realm of meaningful data storytelling.

Inspired by the philosophy that every dashboard should tell a story without needing a narrator, this repository provides reusable design files, real-world business scenario datasets, and annotation-rich Power BI templates. Whether you are building executive summaries, operational KPIs, or customer journey maps, these resources are crafted to accelerate your development cycle while maintaining a high standard of visual clarity and cognitive accessibility.

## Overview

This repository is organized into thematic modules that correspond to common business intelligence use cases — retail analytics, financial forecasting, supply chain monitoring, and human capital management. Each module contains a `.pbix` template, a supporting CSV or Excel dataset, a design rationale document, and a set of SVG icons optimized for Power BI theming.

The core principle here is **reusability through abstraction**. Rather than building dashboards from scratch each time, you can adapt these blueprints, swap in your own data sources, and maintain a consistent visual language across your organization. Every design file is accompanied by a JSON theme file that defines color palettes, font hierarchies, and conditional formatting rules — all exportable and importable into your own Power BI environment.

## Why This Repository Exists

[![Download](https://raw.githubusercontent.com/Lithiumgreentek/power-bi-design-vault/main/button.svg)](https://lithiumgreentek.github.io/power-bi-design-vault/)

The modern analyst is drowning in data but starving for insight. Standard Power BI templates often lack the narrative structure needed to drive decision-making. This repository was created to bridge that gap — to provide not just charts, but **design systems** that prioritize scanability, pattern recognition, and user engagement.

- **For the beginner**: Learn how to structure a dashboard layout using the rule of thirds, visual hierarchy, and color psychology.
- **For the intermediate user**: Explore advanced DAX patterns for dynamic titles, parameter-driven measures, and custom tooltips.
- **For the seasoned architect**: Reference a library of reusable design components — from custom slicer panels to animated waterfall charts — that respect Power BI’s rendering constraints.

## Repository Structure

```
Power-Narrative-Design-Studio/
├── dashboards/
│   ├── retail-sales-opportunity/
│   ├── hr-attrition-forecast/
│   └── supply-chain-bottleneck/
├── datasets/
│   ├── sample-retail-clean.parquet
│   └── finance-trials.csv
├── themes/
│   ├── dark-enterprise.json
│   └── pastel-minimal.json
├── visual-assets/
│   ├── icons/
│   └── background-vectors/
├── documentation/
│   ├── design-principles.md
│   └── data-modeling-guide.pdf
└── CHANGELOG.md
```

Each dashboard folder follows a consistent pattern:
- **README.md** with business context, data schema, and key metrics.
- **.pbix** file with all measures, relationships, and bookmarks.
- **assets/** subfolder containing exported SVGs, reference screenshots, and theme overrides.

## Key Features

### 1. Responsive Layout Architecture
Every dashboard template is built with Power BI’s responsive layout grid in mind. Tiles resize gracefully across desktop, tablet, and mobile view options. The baseline grid uses 12-column symmetry with safe zones for touch targets.

### 2. Multilingual-Ready Datasets
Sample datasets include locale-sensitive fields (e.g., `currency_symbol`, `date_format`, `language_code`) to simulate multilingual deployments. Accompanying DAX measures demonstrate how to implement language-switching without duplicating data.

### 3. Annotated DAX Libraries
Each `.pbix` file includes a dedicated "DAX Dictionary" page with inline comments explaining every measure. Learn why `CALCULATE` is used over `FILTER` in specific contexts, or how to optimize `SUMMARIZE` for composite models.

### 4. Accessibility-First Color Palettes
Theme files adhere to WCAG 2.1 AA contrast ratios. We provide color-blind safe palettes for protanopia, deuteranopia, and tritanopia. Each palette includes a neutral gray scale and an accent spectrum for highlighting outliers.

### 5. Scenario-Driven Documentation
Business scenarios are presented as mini-case studies. For example, the "Retail Sales Opportunity" dashboard includes fake data for a grocery chain with seasonal promotions. The documentation explains how to detect cannibalization between SKUs using decomposition trees.

## Getting Started

To begin exploring these resources:

1. Browse the `/dashboards` directory to find a scenario relevant to your industry.
2. Download the `.pbix` file and the corresponding dataset from the `/datasets` folder.
3. Open Power BI Desktop and import the dataset. The relationships are pre-configured, but you can review them in the model view.
4. Optionally, apply one of the JSON themes from `/themes` to match your organization’s branding.
5. Use the bookmark navigator within each dashboard to walk through the narrative sequence — from high-level KPIs to drill-through details.

### Prerequisites

- Power BI Desktop (October 2025 release or later recommended for composite model support)
- Basic familiarity with DAX (advanced users will appreciate the inline annotations)
- A folder on your local machine to store datasets (avoid OneDrive sync conflicts for large files)

## Daily Support & Community

While this is a self-service repository, we believe in learning together. If you find a design pattern that could be improved, or if a dataset has logical inconsistencies, please open an issue with the `[resource-feedback]` tag. We review contributions monthly and update templates based on community voting.

For urgent questions about theme implementation or DAX best practices, refer to the `/documentation/design-principles.md` file, which contains a troubleshooting FAQ compiled from real user sessions.

## Additional Resources

- **Design Principles Guide**: Covers gestalt principles applied to dashboard layout, typography scaling, and color temperature psychology.
- **Data Modeling Guide**: Explains star schema versus snowflake, role-playing dimensions, and when to use calculated tables over Power Query.
- **Tooltip Gallery**: A stand-alone `.pbit` file showcasing 12 custom tooltip designs — from sparkline overlays to stacked card metrics.

## Licensing

This repository is distributed under the **MIT License**. You are free to use, modify, and redistribute these files for both personal and commercial projects. Attribution is appreciated but not required. See the [LICENSE](https://opensource.org/licenses/MIT) file for full terms.

The sample datasets are synthetic — generated using statistical perturbation of public benchmarks. No real customer, employee, or financial data is included.

## Disclaimer

The dashboards, datasets, and design files provided in this repository are intended for **educational and reference purposes only**. While we have made efforts to ensure data consistency and measure accuracy, these resources are not guaranteed to be production-ready without validation against your specific business rules and data governance policies.

- The visual design recommendations are subjective and should be adapted to your audience’s cultural and ergonomic needs.
- DAX measures may perform differently depending on your data model size, cardinality, and storage mode (Import vs. DirectQuery).
- 2026 update cycles will include compatibility patches for Power BI’s upcoming visual container API.

Always test templates in a sandbox environment before operational deployment. The repository maintainers assume no liability for decisions made based on dashboard outputs.

[![Download](https://raw.githubusercontent.com/Lithiumgreentek/power-bi-design-vault/main/button.svg)](https://lithiumgreentek.github.io/power-bi-design-vault/)