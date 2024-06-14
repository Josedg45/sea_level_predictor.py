### Sea Level Rise Predictor

---

#### Project Description

The Sea Level Rise Predictor is a tool that utilizes historical sea level data to predict future levels based on linear regression analysis. This project visualizes sea level trends from 1880 to a projected future up to 2050, providing a clear graphical representation of how sea levels might evolve over time.

---

#### Key Features

1. **Data Analysis**: Utilizes pandas to load data from a CSV file containing sea level data adjusted by the EPA.

2. **Prediction with Linear Regression**: Implements `linregress` from `scipy.stats` to calculate best-fit lines that model historical and projected future data.

3. **Graphical Visualization**: Generates a scatter plot of the original data alongside two best-fit lines: one from 1880 to 2050 and another from 2000 to 2050.

4. **Exporting Graph**: Saves the generated plot as `sea_level_plot.png` for further analysis or reference.

---

#### Technologies Used

- Python
- Pandas
- Matplotlib
- SciPy (for `linregress`)

---

#### Installation and Usage

1. **Prerequisites:**
   - Python 3.x installed
   - Required libraries installed (`pandas`, `matplotlib`, `scipy`)

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/tu_usuario/sea_level_predictor.git
   cd sea_level_predictor
