# Software system for utilizing sensors in embedded systems for renewable energy management

This project presents a Smart Energy Management System (SEMS) designed to optimize the integration of renewable and non-renewable energy sources. It includes a sophisticated control system for energy flow management based on real-time weather data, aiming to reduce carbon emissions and enhance energy efficiency.

## Description

SEMS encompasses the following key capabilities:

- Real-time weather data retrieval from an external API.
- Dynamic selection of optimal renewable energy sensors based on weather conditions.
- Analysis of renewable energy production and emissions savings.
- Efficient storage of excess renewable energy in battery storage.
- Controlled release of stored energy to meet demand during low renewable production.
- Future predictions for renewable energy emissions reductions.

It aims to contribute to grid stability and maximize the utilization of renewable energy sources.

## Code Structure

The main components of the code include:

- `Sensor` classes: Provide real-time renewable energy data.
- `EnergyManagementSystem`: Analyzes sensor data to calculate energy and emissions.
- `BatteryStorage`: Stores excess renewable energy and releases it when required.
- `SmartGridController`: Manages energy flow between renewable sources and the battery.
- `FutureEmissionsPredictor`: Predicts future emissions savings through 2050.

## Running the Code

To run the smart grid analytics:

1. Ensure Python 3.x and the required libraries are installed.
2. Obtain API keys for weather and emissions data sources.
3. Update `api_url` and other constants as needed.
4. Run `python smart_grid.py`.
5. Input latitude and longitude when prompted.
6. Review energy production, storage, and predicted emissions data.

## Output

The main outputs include:

- Real-time weather conditions.
- Renewable energy produced.
- Emissions from renewable vs non-renewable sources.
- Excess renewable energy stored and released.
- Predicted renewable energy emissions reductions through 2050.

## Visualization

SEMS includes a visualization module based on Matplotlib for predicting CO2 emission savings. This provides an insightful graphical representation of the impact of renewable energy over time.

## Customization

To customize the system:

- Add additional sensor models.
- Update the emissions factor dictionary.
- Modify the predictor model algorithm.
- Integrate with other weather and emissions datasets.

## Acknowledgements

SEMS acknowledges the following libraries:

- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Requests

## Contributing

Contributions are welcome. Please fork the repository, create a feature branch, commit your changes, and open a pull request.
