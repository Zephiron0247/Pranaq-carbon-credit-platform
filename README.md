# Pranaq - Carbon Credit MRV Platform 

Satellite-ML-Blockchain MRV platform for carbon credit verification.

## Stack
- FastAPI + PostgreSQL 18
- Google Earth Engine (Sentinel-2)
- Solidity smart contract on Sepolia
- Web3.py

## Setup
1. Clone repo
2. Create `.env` file with:
   - DATABASE_URL=postgresql://postgres:PASSWORD@localhost:5433/carbon_credit_db
   - SEPOLIA_RPC_URL=your_rpc_url
   - BLOCKCHAIN_PRIVATE_KEY=your_private_key
3. pip install -r requirements.txt
4. uvicorn main:app --reload

## Contract
Deployed on Sepolia: 0x8d0B4Dbd29ae0a52C1B3d2B4568DFE6aF1032285

## Stages
- Stage 1: ndvi_pipeline.py — Sentinel-2 NDVI/EVI/NDWI pipeline
- Stage 2: ml_scoring.py — ML confidence scoring
- Stage 3: FastAPI backend — 8 endpoints
- Stage 4: Smart contract — ERC-20 carbon credit tokens
