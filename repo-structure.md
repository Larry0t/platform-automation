### Platform / Shared Automation Repository ###

```
platform-automation/
├── cloud/
│   ├── aws/
│   ├── azure/
│   └── gcp/
├── containers/
│   ├── base-images/
│   ├── helm-charts/
│   └── kubernetes-addons/
├── ci/
│   ├── github-actions/
│   └── reusable-workflows/
├── terraform-modules/
└── scripts/
```

Purpose:
 - Reusable, versioned building blocks
 - Used by product repos
 - Owned by platform team (or you, centrally)
