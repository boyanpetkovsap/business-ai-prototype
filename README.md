# Business AI – SAP for Me Prototype

Interactive prototype of the Business AI subscription management experience inside SAP for Me.

## Live demo

Open `index.html` locally, or view the [GitHub Pages deployment](../../).

## Tabs

| Tab | Description |
|-----|-------------|
| **Overview** | AI Units consumption across contracts — line chart + vertical bullet chart with tooltips |
| **Balance Statements** | Contract invoices table with mock data |
| **Consumption** | Tree table switchable between By Product and By Price Category |
| **Usage** | Tenant-level drill-down (click any Tenant ID link) |
| **Activation** | Activate services with terms-acceptance flow |

## Stack

- React 18 + ReactDOM via unpkg CDN (no build step)
- Babel standalone (JSX in-browser transform)
- SAP Horizon design tokens (font family "72", color variables)
- All charts hand-built in SVG

## Running locally

Just open `index.html` in any modern browser — no server required.
