# Pranaq — Carbon Credit MRV Platform

ML + Satellite + Blockchain infrastructure for carbon credit verification, anti-fraud governance, and automated MRV workflows.

---

# Overview

Pranaq is a full-stack MRV (Measurement, Reporting, Verification) platform designed for transparent and scalable carbon credit verification.

The platform combines:
- Sentinel-2 satellite imagery
- NDVI/EVI/NDWI vegetation analysis
- ML-based confidence scoring
- Blockchain-based carbon credit issuance
- Governance and fraud-review workflows

---

# Core Features

## Remote Sensing
- Sentinel-2 imagery analysis
- NDVI vegetation monitoring
- EVI canopy scoring
- NDWI irrigation analysis
- Dry-season consistency checks
- Multi-year ecological monitoring

## Machine Learning
- Confidence scoring engine
- Tree cover gain analysis
- Spatial consistency scoring
- Fraud-risk detection

## Blockchain
- ERC-20 carbon credit tokenization
- Verification-linked minting
- Duplicate mint prevention
- Sepolia smart contract deployment

## Governance Layer
- Admin review workflows
- Borderline project flagging
- Fraud escalation system
- Audit trail generation

---

# System Architecture

```text
Company Dashboard
        ↓
FastAPI Backend
        ↓
Satellite + ML Verification
        ↓
Governance Review Layer
        ↓
Smart Contract Minting
        ↓
Carbon Credit Issuance

# Repositories

| Repository | Purpose |
|---|---|
| [Backend](https://github.com/Zephiron0247/carbon-credit-backend) | FastAPI + ML + Remote Sensing |
| [Smart Contracts](https://github.com/Zephiron0247/carbon-credit-contracts) | Solidity + Hardhat |
| [Admin Dashboard](https://github.com/Zephiron0247/carbon-admin-dashboard) | Government/admin portal |
| [Company Dashboard](https://github.com/Zephiron0247/carbon-company-dashboard) | Company submission portal |
| [Buyer Dashboard](https://github.com/Zephiron0247/carbon-buyer-dashboard) | Buyer marketplace portal |
