# Changelog
All notable changes to this project will be documented in this file.

## 2025-12-03
### A new Map Control Panel has been added, consisting of:
- Layer control: Allows toggling additional map layers, **OpenSea Map** (nautical chart overlay) and **RainViewer Weather**.
- Filter control: Adds interactive filtering for map entities: Show/hide specific **vessel** categories, visibility of **port** and **camera** markers.

<div style="display: flex; gap: 16px;">
  <img src="assets/layer-control.png" alt="layer-control" style="width: 50%;" />
  <img src="assets/filter-control.png" alt="filter-control" style="width: 50%;" />
</div>

## 2025-11-25
- Draw Vessel Outline Geometry on Coverage Map
- Added a (bow), b (stern), c (port), d (starboard) fields to the response of `/api/v1/vessel/nearby`. See https://api.marinesia.com/swagger#/vessel/vessel-get_vessel_nearby

<p align="left">
  <img src="assets/vessel-outline-geometry.png" alt="vessel-outline-geometry" width="640"/>
</p>

## 2025-11-23
- Allowed name filter for vessel profile list API. See https://api.marinesia.com/swagger#/vessel/vessel-get_vessel_profiles
- ETA (Expected Time of Arrival) and dest (Destination) fields. See https://docs.marinesia.com/features/#vessel-location
- Rate Limit page in Documentation. See https://docs.marinesia.com/rate-limit

