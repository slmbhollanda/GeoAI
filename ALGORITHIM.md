# GeoIA - Intelligent Flight Algorithm

## Overview
GeoIA uses a three-stage approach for autonomous mineral prospecting:

### Stage 1: Area Coverage (Ant Colony Optimization)
Based on research by Kato et al. (2025), GeoIA implements ACO-based path planning to minimize flight distance while ensuring 100% area coverage [citation:4].

### Stage 2: Waypoint Compression (Geo-Flow-RDP)
Following Sang et al. (2026), waypoint data is compressed by 99.2%, enabling real-time transmission in weak signal areas [citation:2][citation:6].

### Stage 3: Real-time Detection
Onboard computer vision identifies scheelite fluorescence (365nm UV) and geotags promising locations.

## References
- Sang, X. et al. (2026). Research on intelligent flight route algorithms for mineral exploration. *Gold*, 47(4), 12-19.
- Kato, E.R.R. et al. (2025). A method for planning UAV flight paths using Ant Colony Optimization. *Computers and Electronics in Agriculture*.
