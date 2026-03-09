# Research Concepts

## HRV (Heart Rate Variability)

Heart rate variability reflects the variation between consecutive heartbeats.
It is widely used to assess autonomic nervous system activity.

HRV features commonly include:
- RMSSD
- SDNN
- mean heart rate

These features may reflect physiological stress or metabolic load.

---

## PPG (Photoplethysmography)

PPG measures blood volume changes using optical sensors.

It is commonly used in wearable devices such as:
- smart watches
- pulse oximeters

PPG signals can be used to estimate heart rate and derive HRV features.

---

## Reliability Filtering

Physiological conditions such as stress, exercise, or motion may affect
the reliability of metabolic sensing systems.

A reliability filtering layer can identify periods when inference
should be trusted or rejected.

This project explores HRV-derived features as potential reliability indicators.

