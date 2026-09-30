# devpulse-dashboard-CSI-3150

## Structure

```
devpulse-dashboard/
├── index.html
├── styles.css
└── README.md
```

## Page sections

- **Header**: sticky navigation with the "Deploy Free Cluster" cta
- **Hero**: value proposition and two cta's
- **Features**: Latency Tracking, Log Aggregation, Auto-Remediation
- **Pricing**: Developer, Pro Cluster (most popular), Enterprise Dedicated
- **Workload Estimator**: node count and log throughput form
- **Registration**: API sandbox lead capture form
- **Footer**: copyright and navigation links

## Other notes

- Semantic landmarks only at the document level: `header`, `nav`, `main`, `section`, `article`, `footer`
- Heading order: `h1` (hero), `h2` (each section), `h3` (cards)
- CSS: universal `border-box` reset, Flexbox for header/hero/footer
