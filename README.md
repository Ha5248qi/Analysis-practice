# Global Weather Data Spatial Analysis

This is a python-based exercise project, rendering a 2-D plot demonstrating average temperature in a certain area.


## Directory Structure

```text
Analysis-practice/
├── data/                   (daily_weather_data.csv)
├── notebooks/             (.ipynb)
│   ├── Course_exercise.ipynb
├── environment.yml        
├── .gitignore             
└── README.md              
```

## Setup and Reproduction

   ```bash
   git clone [https://github.com/ha5248qi/Analysis-practice.git](https://github.com/ha5248qi/Analysis-practice.git)
   cd Analysis-practice
   conda env create -f environment.yml
   conda activate climate_env
   jupyter lab
   ```
   
## Key Dependencies

dependencies:
  - python=3.12   #There are some differences in different python versions. To avoid breaking down, a python version 3.12 is recommended
  - numpy>=2.0,<3.0
  - matplotlib>=3.11,<4.0
  - jupyterlab
   
## License
This project is with a [MIT license](LICENSE) open-source license.
   