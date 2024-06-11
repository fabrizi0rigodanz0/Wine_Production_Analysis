# Dionysus - Wine Production Analysis 

## Project Description:  
Welcome to Project Dionysus, a venture into the world of wine production analysis! This project is designed to aggregate and analyze data from multiple wine producers. Initially, we focus on monthly bottling outputs from three distinct regions: Almeirim, Benavente, and Cartaxo. The goal is to develop tools that can be scaled up to handle similar datasets efficiently in the future.

##Installation Instructions:
```bash
git clone https://github.com/your-username/dionysus.git
cd dionysus
pip install -r requirements.txt
```

##Data Files:
- `Almeirim.csv`
- `Benavente.csv`
- `Cartaxo.csv`
Each file contains historical monthly output data in thousands of liters from the respective producers.

##Technical Description:
- The project utilizes Python for data processing and analysis, including the use of libraries such as pandas and statsmodels for statistical computations.
- The `Wine` class in `wine_analysis.py` is central to our approach, facilitating easy loading, processing, and forecasting of wine production data.

##Repository Contents:
- `README.md`: Project overview and instructions.
- `Almeirim.csv`, `Benavente.csv`, `Cartaxo.csv`: Dataset files.
- `wine_analysis.py`: Contains the `Wine` class and other essential scripts.

##How to Contribute:
- Fork the repository.
- Create your feature branch (`git checkout -b feature/AmazingFeature`).
- Commit your changes (`git commit -m 'Add some AmazingFeature'`).
- Push to the branch (`git push origin feature/AmazingFeature`).
- Open a Pull Request.
