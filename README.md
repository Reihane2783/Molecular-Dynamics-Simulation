# Molecular Dynamics Simulation Using Lennard-Jones Potential

A Python-based molecular dynamics simulation of Argon-like particles using the Lennard-Jones potential, Verlet integration, and periodic boundary conditions.

## Overview

This project implements a two-dimensional molecular dynamics simulation to study the motion and interactions of particles under a Lennard-Jones potential.

The simulation includes:

- Initialization of particle positions and velocities
- Lennard-Jones force calculation
- Periodic boundary conditions
- Verlet integration for particle motion
- Kinetic, potential, and total energy calculation
- Temperature estimation
- Particle trajectory analysis
- Real-time particle animation
- Potential-energy visualization

## Physical Model

The interaction between particles is modeled using the Lennard-Jones potential, which describes short-range repulsion and long-range attraction between atoms.

The simulation is performed using reduced units based on Argon parameters, including:

- Characteristic length scale (σ)
- Energy scale (ε)
- Reduced time and velocity units

## Simulation Features

### Particle Dynamics

The particles are initialized in a two-dimensional box and their positions and velocities are updated using the Verlet integration algorithm.

Periodic boundary conditions are applied to simulate an infinite system by allowing particles leaving one side of the box to re-enter from the opposite side.

### Energy and Temperature Analysis

During the simulation, the following quantities are calculated:

- Kinetic energy
- Potential energy
- Total energy
- Temperature evolution

These quantities are analyzed to monitor the stability and behavior of the system.

### Visualization

The project generates:

- Initial particle configuration
- Final particle configuration
- Particle motion animation
- Particle trajectories
- Energy evolution plots
- Temperature evolution
- Lennard-Jones potential curve

## Results

The simulation demonstrates:

- Particle motion under interatomic forces
- Conservation of total energy during integration
- Effect of Lennard-Jones interactions on particle dynamics
- Evolution of microscopic particle trajectories

## Technologies

- Python
- NumPy
- Matplotlib
- Matplotlib Animation
- Pillow
