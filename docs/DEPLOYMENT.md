# Deployment Guide

## Profile README

The profile README is at `KaranSaun/KaranSaun`. Push to main → live immediately.

## Brand System

The brand system lives at `KaranSaun/github-brand-system`. It is a separate repository that assets are served from via raw.githubusercontent.com.

## GitHub Actions

All workflows are in `.github/workflows/`. They run on schedule or on push.

### Required Secrets

| Secret | Used By |
|---|---|
| `GITHUB_TOKEN` | All workflows (auto-provided) |
| `METRICS_TOKEN` | metrics.yml (needs a PAT with repo scope) |

## Asset URLs

Assets are served from:
`https://raw.githubusercontent.com/KaranSaun/github-brand-system/main/assets/...`

Update the profile README URLs if the asset path changes.
