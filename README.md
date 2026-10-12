# mPredictor

Static page that estimates the chance of a Tamil Nadu medical counselling seat from a rank, based on past counselling results.

- **DGNM** – government college seats, from the community rank (2025 results).
- **MBBS / BDS** – 7.5% Govt school, general (92.5%) and management quota seats, from the community rank (overall rank for OC, management rank for management quota). Based on 2025 results, with the 2026 Round 1–2 last ranks shown.

`data/dgnm.json` and `data/mbbs.json` hold aggregates only: seat counts and the last rank allotted per college, community and round. They contain no names or application numbers. They are generated from a separate private source with `mpredictor_build_dgnm.py` and `mpredictor_build_mbbs.py`.
