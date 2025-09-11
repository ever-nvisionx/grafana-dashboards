# GitSync Repository for Grafana Dashboards

## Structure
```
├── dashboards/          # Grafana dashboards (JSON)
├── datasources/         # Data source configurations
├── alerts/              # Alert rules
└── README.md           # This file
```

## Usage
1. Push this repository to GitHub
2. Configure GitSync in Grafana to point to this repository
3. Any changes to JSON files will sync automatically to Grafana

## Dashboard Guidelines
- Use unique UIDs for each dashboard
- Include proper tags for organization
- Test locally before pushing changes
