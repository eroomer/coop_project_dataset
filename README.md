# coop_project Dataset

## Purpose
This dataset is used ONLY for system-level testing.
It is NOT intended for model training.

## Structure
- base/      : Normal surveillance scenes (person, vehicle)
- emergency/ : Emergency scenes (fire, smoke, accident)

## Priority Policy
- base       → normal priority queue
- emergency  → high priority queue

## Source
- Base images: VisDrone Dataset (Top-view only)
- Emergency images: Kaggle / Google Search

## Note
This dataset is designed to validate:
- asynchronous processing
- priority queue routing
