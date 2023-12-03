# Software system for utilizing sensors in embedded systems for renewable energy management

This project presents a Smart Energy Management System (SEMS) designed to optimize the integration of renewable and non-renewable energy sources. It includes a sophisticated control system for energy flow management based on real-time weather data, aiming to reduce carbon emissions and enhance energy efficiency.

## Description

The system has the following key capabilities:

- Get real-time weather data from an API 
- Select optimal renewable energy sensors based on weather conditions
- Analyze renewable energy production and emissions savings
- Store excess renewable energy in battery storage  
- Release stored energy to meet demand when renewable production is low
- Predict future renewable energy emissions reductions 

It aims to promote grid stability and maximize renewable energy utilization.

## Code Structure

The main code components:

- `Sensor` classes - Provides real-time renewable energy data 
- `EnergyManagementSystem` - Analyzes sensors data to calculate energy and emissions
- `BatteryStorage` - Stores excess renewable energy and releases when required  
- `SmartGridController` - Controls energy flow between renewable sources and battery
- `FutureEmissionsPredictor` - Predicts future emissions savings through 2050
  

## Running the Code

To run the smart grid analytics:

1. Ensure Python 3.x and required libraries are installed 
2. Get API keys for weather and emissions data sources
3. Update `api_url` and other constants as needed
4. Run `python smart_grid.py`
5. Input latitude and longitude when prompted
6. Review energy production, storage and predicted emissions data

## Output

The main outputs are:

- Real-time weather conditions
- Renewable energy produced
- Emissions from renewable vs non-renewable sources  
- Excess renewable energy stored and released
- Predicted renewable energy emissions reductions through 2050


## Visualization

The system includes matplotlib-based visualization for predicting CO2 emission savings, offering an insightful graphical representation of the impact of renewable energy over time.

## Customization

To customize the system:

- Add additional sensor models
- Update the emissions factor dictionary
- Modify predictor model algorithm
- Integrate with other weather and emissions datasets

## Acknowledgements
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Requests

## Contributing

Contributions are welcome. Please fork the repository, create a feature branch, commit your changes, and open a pull request.
