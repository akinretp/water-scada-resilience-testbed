# SCADA Testbed Implementation for Water and Wastewater Cyber Resilience

I implemented a ScadaBR-based cybersecurity testbed to compare how four water and wastewater architectures respond to operational disruptions. The workflow combines system dynamics models and SCADA telemetry to assess how process conditions change over time.

The study covers Center Water, seawater reverse osmosis (SWRO), SWAT, and Wastewater.

## Featured result

[View the tank leakage comparison (PDF)](leakage_comparison.pdf)

The figure compares total stored water volume during a simulated **15 L/min tank leak**. It illustrates how the same disturbance can produce different storage responses depending on the architecture. Stored volume measures the water remaining in the modeled system. Service continuity would require separate delivery or unmet-demand measurements.

## Related portfolio work

- [Water Resilience Lab](https://github.com/akinretp/water-resilience-lab) compares service continuity and reserve recovery during a supply interruption.
- [Four-architecture structural comparison](https://github.com/akinretp/water-network-resilience-demo) compares component dependencies across the four modeled architectures.
