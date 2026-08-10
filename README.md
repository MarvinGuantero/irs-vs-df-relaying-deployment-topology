# Impact of Deployment Topology on the Performance Trade-off Between IRS versus Decode-and-Forward Relaying in Wireless Communication Systems

## Overview

This repository contains the simulation codes, figures, and supporting materials for the research paper:

> **Impact of Deployment Topology on the Performance Trade-off Between IRS versus Decode-and-Forward Relaying in Wireless Communication Systems**

**Authors**
- Marvin A. Guantero
- Aaron Don M. Africa

Department of Electronics, Computer, and Electrical Engineering  
De La Salle University  
Manila 1004, Philippines

**Corresponding Author**
- Marvin A. Guantero
- Email: marvin_guantero@dlsu.edu.ph

---

## Abstract

Intelligent Reflecting Surfaces (IRS) have emerged as a promising technology for improving wireless communication performance through programmable passive beamforming. While previous studies have extensively compared IRS-assisted communications with Decode-and-Forward (DF) relaying, most assume fixed deployment geometries, leaving the impact of node placement largely unexplored.

This work investigates how deployment topology influences the performance trade-off between IRS and DF relaying in terms of:

- Required transmit power
- Signal-to-Noise Ratio (SNR)
- Achievable rate
- Energy efficiency

Using extensive Monte Carlo simulations with **10,000 randomized deployments** under the **3GPP Urban Micro (UMi)** channel model, this study demonstrates that deployment geometry significantly affects the comparative performance of IRS and DF relaying.

---

## Key Contributions

The main findings of this work include:

- **Topology-dependent deployment strategies**
  - IRS achieves its best performance when deployed asymmetrically near either the source or destination.
  - DF relay performs optimally when positioned approximately midway between the source and destination.

- **Placement-dependent power advantage**
  - The transmit power difference between IRS and DF relaying can exceed **15 dB**, depending on deployment geometry.

- **Optimal IRS size**
  - Increasing the number of reflecting elements does not always improve energy efficiency.
  - A topology-dependent optimal number of IRS elements exists that balances passive beamforming gain and circuit power consumption.

- **Practical deployment guidelines**
  - Node placement should be treated as a first-order design variable when comparing IRS-assisted and relay-assisted wireless communication systems.

---

## Simulation Configuration

The simulations are based on:

- 3GPP Urban Micro (UMi) channel model
- Monte Carlo simulations
- 10,000 randomized deployment realizations
- Passive IRS beamforming
- Decode-and-Forward relaying
- Power minimization framework
- Energy efficiency analysis

---

## Research Highlights

This repository investigates:

- IRS deployment optimization
- Relay placement optimization
- Deployment topology analysis
- Required transmit power
- SNR performance
- Achievable rate
- Energy efficiency
- IRS versus DF relay comparison

---

## Citation

If you use this repository in your research, please cite:

```bibtex
@article{Guantero2026,
  author = {Marvin A. Guantero and Aaron Don M. Africa},
  title = {Impact of Deployment Topology on the Performance Trade-off Between IRS versus Decode-and-Forward Relaying in Wireless Communication Systems},
  journal = {Under Review},
  year = {2026}
}
```


---

## License

This repository is released for academic and research purposes.

Please cite the original paper if you use the simulation code or reproduce any figures.

---

## Contact

**Marvin A. Guantero**

Department of Electronics, Computer, and Electrical Engineering  
De La Salle University

Email: marvin_guantero@dlsu.edu.ph

---

## Keywords

Intelligent Reflecting Surface (IRS), Decode-and-Forward Relaying, Wireless Communications, 6G, Deployment Topology, Passive Beamforming, Monte Carlo Simulation, Energy Efficiency, Power Optimization, 3GPP Urban Micro.
