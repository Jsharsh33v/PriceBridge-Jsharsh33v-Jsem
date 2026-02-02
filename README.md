# PriceBridge-Jsharsh33v

PriceBridge is a web-based interactive application designed to support
introductory economics courses (Econ 100/101), covering both
microeconomics and macroeconomics.

The project is built around the idea of acting as a *bridge* between how
economic theory is taught in class and how real markets behave in the
real world. Introductory economics often relies on simplified equations
and graphs, which can feel disconnected from actual economic data.
PriceBridge helps close this gap by combining standard Econ 100/101
models with real-world data to provide context and intuition.

The application allows students to interactively modify economic model
parameters and immediately observe how equilibrium outcomes, graphs,
and interpretations change, reinforcing the connection between theory,
data, and intuition.

The application is implemented in Python, with Streamlit used to provide
an interactive web interface that runs in a browser without requiring
users to install Python or additional software.

## Educational Focus

PriceBridge is designed as a learning tool rather than a predictive or
fully realistic economic model. Its primary goal is to help students
understand *how* economic theory works, *why* assumptions matter, and
*how* simplified models relate to real economic conditions.

The project emphasizes:
- Understanding cause-and-effect in economic models
- Linking equations to graphs and economic intuition
- Exploring counterfactual scenarios in a controlled environment
- Using real data to ground abstract theory in observable outcomes

Simplified economic equations are used intentionally to match the level
and structure of Econ 100/101 courses, while real-world data is used to
calibrate baseline values and provide meaningful context.

## Planned Scope

### Microeconomics
- Linear supply and demand equations
- Market equilibrium (price and quantity)
- Parameter changes and curve shifts
- Price elasticity intuition
- Simple policy analysis (e.g., per-unit taxes)
- Interpretation of results in relation to real markets

### Macroeconomics
- Aggregate demand and aggregate supply framework
- Equilibrium output and price level
- Short-run economic shocks
- Visualization of macroeconomic adjustments
- Connections between model outcomes and observed economic data

## Data Sources and Real-World Context

The application will incorporate real, publicly available economic data
to anchor models in actual market conditions. Planned data sources
include:

- Federal Reserve Economic Data (FRED) for macroeconomic indicators such
  as GDP and inflation
- U.S. Bureau of Labor Statistics (BLS) for price indices and market-level
  data

Rather than attempting to estimate fully realistic models, this data is
used to:
- Set reasonable baseline values
- Provide realistic scales and magnitudes
- Help students interpret model outcomes in a real-world context

This approach reflects how introductory economics uses simplified
theory to reason about real markets without claiming perfect accuracy.

## Planned Features
- Interactive number inputs and sliders
- Real-time graph updates
- Automatically computed equilibrium values
- Visual highlighting of curve shifts
- Short explanations describing economic intuition
- Comparisons between baseline (data-informed) and modified scenarios

## Technologies
- Python
- Streamlit
- NumPy
- Pandas
- Matplotlib

## Project Status
This repository currently contains the initial project structure and
documentation. Core economic models, data integration, and the user
interface will be implemented incrementally.

## How the Application Will Run
The application will be deployed as a hosted web app.
Users will interact with the model through a web browser without
needing to configure a local programming environment.