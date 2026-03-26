# CORDProj_38616

Risk-aware verification for financial document processing using CORD and SROIE datasets.

## Project Overview

This project focuses on building a cost-sensitive decision system for automated receipt extraction pipelines. The goal is to use model uncertainty and consistency signals to decide when to accept outputs versus trigger verification.

Core idea:
image → extraction → risk score → (accept vs verify)

## Datasets

- CORD: ~11k receipts with OCR text, layout, and structured labels  
- SROIE: ~1k receipts with labeled key fields (total, date, company, address)

## Setup

Clone the repository:

git clone <repo_url>  
cd CORDProj_38616

Create the data directory:

mkdir Data

Download datasets:

- CORD → place in:
Data/cord/

- SROIE → place in:
Data/sroie/
