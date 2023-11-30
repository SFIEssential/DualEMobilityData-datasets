# DualEMobilityData-datasets
Welcome to our repository focused on E-Bike and E-Scooter trips. We aim to offer open-source datasets for E-Mobility research, particularly in urban commuting using electric bikes and scooters. These datasets, collected around Dublin City University, consider key factors influencing energy consumption.

# Dataset Description
Our datasets are divided into two parts: E-Bike and E-Scooter trips, totaling 36 and 30 trips, respectively. The E-Bike data were collected using the Electric Trekking Bike T1 of Eleglide E-Bike Eleglide E-Bike, and the E-Scooter data from the Mi Electric Scooter Pro 2 of Xiaomi E-Scooter Xiaomi E-Scooter.

## E-Bike Dataset
The E-Bike featured in our dataset includes a 250 W motor with a top speed of 25 km/h, a range of 100 km, and a 450 Wh battery. It is equipped with a power assist module offering five levels of assist/electric mode corresponding to different speeds. Our dataset captures various real-world scenarios by including trip attributes for different pedal assist levels.

### Data Collection Setup
We employed the iGS630 of iGPSPORT GPS Bike Computer iGPSPORT GPS Bike Computer and LivLov V2 Bike Cadence and Speed Sensors LivLov V2 Sensors for data collection. Attributes such as timestamps, GPS coordinates, altitude, speed, assistance level, and distance were recorded.

### Data Processing
Key steps in data processing include:

Data Integration: Merging data from devices for a unified dataset.
SOC Calculation: Using a custom nonlinear equation for accurate SOC estimation.
Energy Efficiency Calculations: Measuring energy consumption and efficiency.
Weather Data Incorporation: Adding weather data from Weather25 Weather25.
Synthetic Data Generation: Creating a synthetic dataset with Python's Synthetic Data Vault library.

## E-Scooter Dataset
Our E-Scooter dataset features the Mi Electric Scooter Pro 2, equipped with a 600-watt motor and a high-capacity 446 Wh lithium battery. The scooter offers three speed modes, and our data collection focused on the sports mode (0-25 km/h).

### Data Collection Setup
Data attributes were collected using two mobile applications: Mi Home for the Xiaomi E-Scooter Mi Home App and GPS-Tracker Pro for tracking GPS-Tracker Pro.

### Data Processing
The process includes:

Digit Extraction: Using pytesseract Pytesseract for SOC extraction.
Data Integration: Integrating data from mobile applications using timestamps.
Weather Data Incorporation & Data Generation: Employing methods similar to the E-Bike dataset.
Usage and Contribution
This repository is open for academic and research purposes. We encourage contributions and feedback to enhance the datasets' quality and applicability. Please follow the contribution guidelines for submitting your improvements or use cases.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
