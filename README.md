# GTM Templates

Raccolta di template GTM, snippet dataLayer e configurazioni GA4 pronti per il deployment.

## Struttura

```
gtm-templates/
├── web/           # Container GTM web (JSON export)
├── datalayer/     # Snippet dataLayer (JS)
├── ga4-config/    # Configurazioni GA4 (custom dimensions, measurement protocol)
└── snippets/      # Script utility standalone
```

## Convenzioni

- Ogni template ha la sua sottocartella con README.md e file principale
- Versioning semantico nel nome file: template-name_v1.0.json
- CMS target indicato nel README di ogni template

## Stack di riferimento

GTM web + sGTM, GA4, Consent Mode v2, Iubenda CMP, Stape
