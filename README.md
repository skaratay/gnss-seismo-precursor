# gnss-seismo-precursor

Multi-parameter GNSS-based seismo-ionospheric precursor detection using 
PPP-derived tropospheric features and LOEO-SVM classification.

## Associated publication
Karatay, S. (2025). PPP-Derived Tropospheric Parameters Outperform TEC 
in Multi-Channel GNSS Seismo-Ionospheric Precursor Detection. 
*Computers & Geosciences*. (under review)

## Repository contents
- `EQ_Precursor_Detection_codes.txt` — Main MATLAB pipeline (rename to `.m` before running)
- `CHILE_2010_ALL.xlsx` — Input data: 2010 Maule, Chile (Mw 8.8)
- `ECUADOR_2016_ALL.xlsx` — Input data: 2016 Pedernales, Ecuador (Mw 7.8)
- `JAPAN_2011_ALL.xlsx` — Input data: 2011 Tōhoku, Japan (Mw 9.1)
- `JAPAN_2024_ALL.xlsx` — Input data: 2024 Noto Peninsula, Japan (Mw 7.5)
- `MARAS_2023_ALL.xlsx` — Input data: 2023 Kahramanmaraş, Türkiye (Mw 7.8)
- `MAYOTTE_2018_ALL.xlsx` — Input data: 2018 Mayotte (Mw 4.3)

## Requirements
- MATLAB R2016b or later
- Statistics and Machine Learning Toolbox

## Usage
1. Rename `EQ_Precursor_Detection_codes.txt` to `EQ_Precursor_Detection.m`
2. Set `DATA_DIR` at the top of the script to the folder containing the xlsx files
3. Run the script in MATLAB

## Data sources
- GNSS RINEX: IGS (https://www.igs.org) and GEONET/GSI (https://www.gsi.go.jp)
- PPP processing: CSRS-PPP (https://webapp.csrs-scrs.nrcan-rncan.gc.ca)
- TEC: IONOLAB (https://www.ionolab.org)
- Earthquake catalogue: USGS (https://earthquake.usgs.gov)

## License
MIT License — see LICENSE file for details.
