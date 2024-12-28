# Mining and Water Event Data Analysis

This repository contains a collection of Jupyter notebooks designed to analyze the intersection of mining activities and water-related events, incorporating multi-dimensional data such as well. The project utilizes data from the Global Knowledge Graph (GKG), the Global Database of Events, Language, and Tone (GDELT), and additional socioeconomic and environmental datasets.

## Contents

**1. mining_water_GKG.ipynb** - Downloads and processes GKG data related to mining and water themes.
**2. mining_event.ipynb** - Contains the code for downloading and processing event data from GDELT.
**3. mining_water_GKG_event_data.ipynb** - Merges the processed GKG and event data, performs advanced filtering, and prepares the data for analysis.
**4. data_analysis_and_modeling.ipynb** - Merges multidimensional data including socioeconomic and environmental datasets with the previously merged data. This notebook is used for comprehensive data analysis and to build Generalized Linear Models (GLM) for further insights.

## Getting Started

#### Prerequisites

- Python 3.9.13 or later
- Jupyter Notebook
- Required libraries: numpy, pandas, requests, beautifulsoup4, pathos, tqdm, hashlib, json, urllib, goose3, langid, and additional libraries for data analysis and modelling.

#### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mining-water-event-data.git
