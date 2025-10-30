# Informatica XML → Excel / DDL / PDF (FastAPI) — Render Deployment

This service accepts an Informatica PowerCenter XML upload and returns a ZIP containing:
- Business_Summary.xlsx
- <TargetName>.sql
- Mapping_Summary_VAAMG.pdf (VAAMG brand color/name/tagline)

## Deploy with Render Blueprint
- Go to https://dashboard.render.com/iac → New Blueprint → Select your repo

## Or create a Web Service manually
- New → Web Service → Connect repo
- Environment: Docker; Dockerfile Path: Dockerfile
- Start command controlled by Dockerfile
