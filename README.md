# NeutronTransport
Simulating neutron behavior in nuclear systems using Monte Carlo & deterministic methods. 

## What it Does
- Models neutron transport through media
- Monte Carlo simulations +/or deterministic solvers
- Supports cross-section input and boundary conditions
- Outputs flux, reaction rates, leakage, etc.
- (Optional) Comes with plotting for visualization

## Getting Started
### 1. Clone & activate
        
git clone https://github.com/rgorasia19/NeutronTransport.git
cd NeutronTransport
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

### 2. Install requirements

pip install -r requirements.txt

## Requirements
- Python 3.8+ (or your language of choice)
- numpy, pandas
- matplotlib/seaborn (for plotting)
- tqdm (progress bar)
- Optional: scipy, numba, jupyter

## Extending It
- Add 2D/3D geometries
- Integrate advanced methods like variance reduction
- Output tally-specific data
- Add file parsers for ENDF-format cross-sections

## License
Apache-2.0 License. Use it and learn from it
