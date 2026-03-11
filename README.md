# NinjaRepo

Public file repository for Kern Energy IT — used by NinjaOne RMM automations to download configuration files via raw GitHub URLs during script execution.

## Contents

### Microsoft 365 — Office Deployment Tool (ODT) Configs

XML configuration files for silent Office 365 deployments using `setup.exe /configure`.

| File | Product | Architecture |
|------|---------|--------------|
| `Office_365_32bit_Business.xml` | Microsoft 365 Apps for Business | 32-bit |
| `Office_365_64bit_Business.xml` | Microsoft 365 Apps for Business | 64-bit |
| `Office_365_32bit_Enterprise.xml` | Microsoft 365 Apps for Enterprise (ProPlus) | 32-bit |
| `Office_365_64bit_Enterprise.xml` | Microsoft 365 Apps for Enterprise (ProPlus) | 64-bit |
| `Project_365_32bit.xml` | Project Pro | 32-bit |
| `Project_365_64bit.xml` | Project Pro | 64-bit |
| `Visio_Plan_2_32bit.xml` | Visio Plan 2 (Pro) | 32-bit |
| `Visio_Plan_2_64bit.xml` | Visio Plan 2 (Pro) | 64-bit |

All configs are scoped to the Kern Energy Microsoft 365 tenant, set to the Current update channel, with OneDrive (Groove) and Skype for Business (Lync) excluded where applicable.

## Usage

Raw file URLs follow this pattern:

```
https://raw.githubusercontent.com/<org>/NinjaRepo/main/<filename>.xml
```

Reference these URLs in NinjaOne script parameters or directly in ODT deployment automations.

## Maintainer

Kern Energy IT — Systems Administration
