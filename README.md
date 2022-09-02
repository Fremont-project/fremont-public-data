# Fremont Example Dataset
Processed public data for Fremont. This repository serves as an example data source to run the open-source Aimsun microsimulation codebase at [traffic-microsimulation](https://github.com/Fremont-project/traffic-microsimulation).

An example Fremont [output database file](https://drive.google.com/file/d/15UCl9_HqB00rI6cYKEUk-B02Xqq8EAy3/view?usp=sharing) is available for download if you wish to access how the output looks like without running the Aimsun simulation itself. Please put this sqlite file into `fremont-public-data/aimsun/outputs/fremont_example/output_database.sqlite` and you will be able to run the microsimulation analysis notebook at `traffic-microsimulation/calibration/microsimulation_config_and_analysis.ipynb`.

## Structure
- `aimsun`: Folder that contains all Aimsun input and output data. The input is provided, and the output can be created by running our microsimulation codebase.
- `fremont_example_network.ang`: Aimsun network file for Fremont. This network contains the Fremont road network, as well as pre-populated Master Control Plans.
