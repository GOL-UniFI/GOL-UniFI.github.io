---
layout: page
title: AIMS
permalink: /pages/projects/sii_mobility/
---


# Multi-Objective Route Planning on Multimodal Networks

**Sii-Mobility Project - Research Contribution**

---

## Overview

The **Sii-Mobility** project focuses on integrated transportation solutions for smart cities. Our contribution provides state-of-the-art algorithms for **optimal path planning on multimodal, multi-objective transportation networks**.

**Deliverable:** State-of-the-art in multi-objective optimal path problems on multimodal graphs

---

## The Challenge

Modern urban mobility requires handling:
- **Multiple transportation modes** (walking, transit, cycling, driving)
- **Multiple optimization criteria** (time, transfers, cost, emissions)
- **Time-dependent networks** (schedules, traffic, real-time delays)
- **Large-scale networks** (metropolitan-size graphs)

Traditional algorithms struggle with this complexity.

---

## Our Research Focus

### 1. Urban Road Networks

Advanced speed-up techniques for fastest route computation:
- **Goal-directed methods** - A*, ALT (landmarks and triangle inequality)
- **Hierarchical techniques** - Contraction Hierarchies, Arc Flags
- **Hybrid approaches** - SHARC, CHASE combining multiple methods
- **Dynamic networks** - handling real-time traffic conditions

### 2. Public Transportation

Specialized algorithms for timetable-based routing:
- **Time-dependent modeling** - FIFO property, travel time functions
- **RAPTOR algorithm** - round-based public transit optimization
- **Transfer patterns** - ultra-fast query times
- **Real-time integration** - delays and cancellations

### 3. Multi-Objective Optimization

Finding complete sets of optimal trade-off solutions:
- **Pareto-optimal routes** - all non-dominated alternatives
- **Multi-label algorithms** - MLS, MLC for exact solutions
- **Bi-criteria methods** - arrival time vs. number of transfers
- **Approximate techniques** - handling large solution spaces efficiently

### 4. Multimodal Integration

Combining different transportation modes:
- **Multimodal Multicriteria RAPTOR (MCR)** - extending transit algorithms
- **Graph fusion** - connecting road, transit, pedestrian networks
- **Mode transitions** - realistic transfer times and costs

---

## Key Findings

| Algorithm | Best Application | Key Advantage |
|-----------|-----------------|---------------|
| **Dijkstra** | Baseline | Simple, guaranteed optimal |
| **Contraction Hierarchies** | Static road networks | Millisecond queries |
| **RAPTOR** | Public transit | Natural multi-objective, very fast |
| **MCR** | Multimodal journeys | Handles complex multi-criteria scenarios |

**Main Insight:** No single algorithm dominates all scenarios. The optimal choice depends on network characteristics, query requirements, and dynamic vs. static data.

---

## Impact

**For Cities:**
- Ultra-fast route computation (millisecond response times)
- Multiple route alternatives showing different trade-offs
- Scalable to metropolitan networks
- Real-time traffic and transit delay handling

**For Users:**
- Better journey options with clear trade-offs
- Seamless multimodal trip planning
- Personalized preferences integration

---

## Technical Foundation

- **Graph theory** - directed, weighted graph modeling
- **Dynamic programming** - optimal substructure exploitation
- **Multi-objective optimization** - Pareto dominance
- **Computational complexity** - practical solutions to NP-hard problems

---

## Applications

- Journey planning apps (Google Maps, transit apps)
- Fleet management and vehicle routing
- Emergency services routing
- Urban accessibility analysis
- Mobility-as-a-Service (MaaS) platforms

---

## Team

**dr Luca Tigli, PhD** - Algorithm design and analysis  
**Prof. Fabio Schoen** - Project coordination

University of Florence, Department of Information Engineering

---

## Key References

- Dijkstra (1959) - Shortest path algorithm
- Delling et al. (2013-2015) - RAPTOR and multimodal routing
- Bast et al. (2015) - Comprehensive route planning survey
- Geisberger (2011) - Advanced route planning techniques

---

*Advancing urban mobility through algorithmic innovation for smarter, more sustainable cities.*
