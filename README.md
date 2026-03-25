# Alpine Range Guardian

Building AI course project

## Summary
Alpine Range Guardian is an AI assistant that prevents "range anxiety" for e-bike riders in mountainous regions like the Austrian Alps. By combining real-time sensor data from bikes like the Specialized Vado 5.0 with topographic elevation maps, it provides ultra-accurate battery predictions and smart power-saving advice for steep climbs.

## Background
* **The Problem:** Standard e-bike range estimators fail in the mountains; a 10% incline drains batteries 5x faster than flat roads.
* **Frequency:** This is a common issue for alpine commuters and tourists.
* **Personal Motivation:** As I move from a maritime career to the Austrian hills, I want to rely on my Specialized Vado 5.0 as a primary sustainable vehicle.

## Data and AI techniques
* **Data Sources:** E-bike sensors (Watts, cadence, battery voltage) via the Specialized Mission Control API and GPS elevation models.
* **AI Techniques:** Regression Models to predict energy consumption and Neural Networks to learn the rider's unique effort profile.

## How is it used?
The solution is integrated into a smartphone app. The rider enters a destination, and the AI suggests the optimal support mode to ensure they reach their destination safely.

## Challenges
* Environment: Wind speed and weather are hard to predict.
* Weight: The model needs to account for extra cargo.

## What next?
The project could scale into a B2B Fleet Management tool for alpine rental companies.

## Acknowledgments
* Inspired by the Building AI course.
