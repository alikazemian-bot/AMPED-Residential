AMPED-Residential: Agent-based Model for Predicting Electricity Demand

Authors:

Ali Kazemian<sup>1</sup>, Baxter Kamana-Williams<sup>1,2*</sup>, J. Geoffrey Chase<sup>1</sup>
<sup>1</sup>Department of Mechanical Engineering, University of Canterbury, Christchurch, New Zealand
<sup>2</sup>Sustainable Energy Research Group (SERG), Department of Civil and Environmental Engineering, University of Canterbury
Corresponding author: baxter.williams@pg.canterbury.ac.nz


Overview

AMPED-Residential is an open-source, generalisable agent-based model (ABM) of residential electricity demand.
It generates minute-level household load profiles for existing and emerging residential loads, including electric vehicles, solar PV, and battery storage.
The model supports demand-side management (DSM) research, policy analysis, and energy system planning across diverse socioeconomic and climatic contexts.


Repository Structure

AMPED-Residential/

│

├── AMPED-Residential Agent-based Model for Predicting Electricity Demand.ipynb

│   └─ Main simulation file containing the full agent-based model

│

├── Appliance profiles.xlsx

│   └─ Average appliance use behaviour and power ratings

│

├── dm_050.csv

├── dm_100.csv

├── dm_150.csv

├── dm_200.csv

├── dm_250.csv

│   └─ Domestic hot water (DHW) demand profiles generated using DHWcalc

│      (approx. 50–250 L/day, representing households with 1–5+ people)

│

├── tmy_Auckland.csv

├── tmy_Wellington.csv

├── tmy_Christchurch.csv

│   └─ Typical Meteorological Year (TMY) climate data from NIWA

│      including ambient temperature and solar irradiance for each city

└── LICENSE.txt (MIT License)



Prerequisites

Python ≥ 3.9
Recommended packages: numpy, pandas, matplotlib, openpyxl, tqdm


Running the Model

Clone this repository
Open the main notebook: "AMPED-Residential Agent-based Model for Predicting Electricity Demand.ipynb"
Edit the input parameters and scenario settings as required (see the Pre-processing section of the notebook).


Outputs

Minute-resolution electricity demand (per household and aggregate)
Load breakdowns by appliances, water heating, space heating/cooling, lighting, EVs, PV, and batteries
Summary statistics, peak demand analysis, and CSV exports for post-processing


Citation

Kazemian A., Kamana-Williams B.L.M., Chase J.G. (2025).
AMPED-Residential: Agent-based Model for Predicting Electricity Demand.
University of Canterbury, Aotearoa New Zealand.
