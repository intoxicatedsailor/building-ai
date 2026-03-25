Building AI course project

## Summary
Alpine Range Guardian is an AI assistant that prevents "range anxiety" for e-bike riders in mountainous regions like the Austrian Alps. By combining real-time sensor data from bikes like the Specialized Vado 5.0 with topographic elevation maps, it provides ultra-accurate battery predictions and smart power-saving advice for steep climbs.

## Background
* **The Problem:** Standard e-bike range estimators fail in the mountains; a 10% incline drains batteries 5x faster than flat roads.
* **Frequency:** This is a common issue for alpine commuters and tourists.
* **Personal Motivation:** As I move from a maritime career to the Austrian hills, I want to rely on my Specialized Vado 5.0 as a primary sustainable vehicle.

## Data and AI techniques
* **Data Sources:** * E-bike sensors (Watts, cadence, battery voltage) via the Specialized Mission Control API.
    * GPS and Digital Elevation Models (DEM) for slope calculation.
* **AI Techniques:** * **Regression Models** to predict energy consumption based on incline.
    * **Neural Networks** with non-linear activation functions to learn the rider's unique effort profile and fatigue levels over time.

## How is it used?
The solution is integrated into a smartphone app or the bike's head unit. The rider enters a destination, and the AI suggests the optimal support mode (e.g., "Switch to 30% support now") to ensure they reach their "safe haven" at the top of the mountain.

## Challenges
* **Environment:** Wind speed and weather are hard to predict without local sensors.
* **Weight:** The model needs to account for extra cargo or passengers.
* **Hardware:** Optimizing neural networks for low-power bike computers.

## What next?
The project could scale into a B2B Fleet Management tool for alpine rental companies or integrate with green energy grids to suggest charging at renewable hydro/solar stations.

## Acknowledgments
* Inspired by the **Elements of AI / Building AI** course.
* Technical specs based on the **Specialized Turbo Vado 5.0** system.
* Concept developed with help from Gemini AI.
