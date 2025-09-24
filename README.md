## Heat Pump Deployment Priority Analysis – England

The UK Government asked for analysis of England’s housing stock to see where heat pumps should be deployed first and how subsidy funding could be targeted.Using EPC data from 324 local authorities, we ranked areas based on four factors: Cost-effectiveness (value for money), Social equity (helping fuel-poor households), Carbon reduction potential, and Market readiness. Our results show that different regions need different approaches. The findings provide practical recommendations on how to focus limited funding for the biggest social and environmental benefit, while supporting net zero goals and reducing fuel poverty.

## Project Structure
-- Notebook/Data_Exploration.ipynb    # Main analysis

-- data/raw/                          # EPC data (not in git)

-- outputs/                           # Results and figures

-- requirements.txt                   # Python dependencies

-- README.md                          # This file

## Data and reproducibility

The raw EPC extracts and derived files are very large (2GB+), so they are excluded from GitHub via .gitignore to prevent RAM issues and push timeouts.
To reproduce:

## Clone repository
Install dependencies: pip install -r requirements.txt
Download EPC data and place in data/raw/
Run Notebook/Data_Exploration.ipynb

Note: Without the original data files, this repo requires data download for full reproduction.
Dataset

Coverage: 26.8M properties across 324 UK authorities
Source: EPC Database 





