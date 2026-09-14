# 🌧️ SHIELD-X — Urban Flood Nowcasting System

### SIH26085 | Disaster Management | Team Shield-X

**SHIELD-X** is a GIS + AI based urban flood decision-support platform that converts rainfall, terrain, drainage and road-network data into **location-specific flood risk and safer-route intelligence**.

# 🎯 Problem

Urban flood response is often reactive.

Rainfall forecasts may indicate heavy precipitation, but rainfall alone does not explain how water will behave at street level.

The same rainfall event can produce very different outcomes depending on:

- Micro-topography
- Drainage infrastructure
- Surface runoff pathways
- Drainage congestion
- Historical waterlogging
- Road-network exposure

This creates a critical gap between **weather forecasting** and **on-ground flood response**.

SHIELD-X is designed to close this gap through an integrated geospatial and machine-learning workflow.

## 💡 Innovation

- Combines **rainfall nowcasting + DEM/terrain + drainage behaviour + road network** in one system.
- Provides **street/location-level flood risk** instead of only city-wide warnings.
- Connects flood prediction with **flood-aware alternative routing**.
- Designed to integrate citizen reports for continuous ground-level validation.
- Modular architecture allows adaptation to different cities.

## ⚙️ Technical Approach

Rainfall / Radar
      ↓
Rainfall Features
      +
DEM → Elevation • Slope • Flow Accumulation
      +
Drainage Network → Capacity • Risk • Blockage
      +
Road Network + Historical Flood Data
      ↓
   ML / Risk Engine
      ↓
Waterlogging Probability + Flood Risk
      ↓
GIS Dashboard + Safe Route Recommendation
