# Patch-clamp EPSC/IPSC event detection (Python)

## Overview
Reproducible pipeline to detect spontaneous synaptic events (EPSCs/IPSCs) from electrophysiology patch clamp recordings.

Includes: 
- Filetering signal
- Manual stablished threshold based noise/level
- User evaluation of indivial synaptic currents detected to be considered as real synaptic event 
- Final average IPSCs and EPSCs
- Determination of amplitudes of average synaptic currents (ideal to compared between experimental groups)
- Frequency of IPSCs and EPSCs

  
## What’s included
- Notebook workflow (Colab/Jupyter)
- Modular Python functions for IO, filtering, detection, and metrics
- Example figures and simulated sample data


## How to run
### Option A — Google Colab
2) Open and run: `Spontaneous.ipynb`

### Option B — Local
1) `pip install -r requirements.txt`
2) Open and run: `Spontaneous.ipynb`

## Outputs
- Traces of all synaptic events plus average PSCs on as svg to be imported graphical editors (ppt, coreldraw, ilustrator)
- Average EPSCs and IPSCs amplitude distribution
- EPSCs and IPSCs frequencies

## Notes on data
This repository does not include raw experimental ABF files.
Use your own files locally in Colab, or run with the included simulated sample trace.

## Author
David Leonardo García Ramírez, PhD
