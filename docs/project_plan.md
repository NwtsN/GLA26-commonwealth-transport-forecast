# Project Plan (MVP)

## Brief

Goal: Forecast 2026 road traffic on one corridor near [VENUE] for Glasgow 2026, and test a Games-day spectator scenario.

Data:
- DfT Road Traffic Statistics API (AADF 2000–2024) for one count_point_id

Method:
- Simple time-series / regression forecast for 2026
- Add spectator car demand scenario
- Stress index = Games-day AADF / historic max AADF

Deliverable:
- `notebooks/glasgow_2026_mvp.ipynb` as a report
- README with summary + key plot
