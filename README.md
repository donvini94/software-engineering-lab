# Integration of Performability Analyses into CI/CD Pipeline

## Overview
This lab report details the design and implementation of a CI/CD pipeline for automated performability analysis, combining performance and reliability measurements of systems. The project integrates PMX (Performance Model eXtractor) from the University of Würzburg and the Palladio Simulator from KIT into an automated workflow.

## Key Contributions
- Developed a complete CI/CD pipeline for performability analysis automation
- Successfully replicated the FZI infrastructure environment using NixOS
- Implemented Docker containerization for analysis tools:
  - PMX container for model extraction
  - Palladio container for simulation
  - Gnuplot container for results visualization

## Technical Implementation
- **Infrastructure Setup**
  - NixOS-based server configuration
  - GitLab instance with custom Docker registry
  - Multi-stage CI/CD pipeline architecture
  
- **Pipeline Design**
  - Extract stage: PMX analysis and data extraction 
  - Simulate stage: Palladio-based simulation
  - Plot stage: Results visualization using Gnuplot

- **Containerization**
  - Custom Dockerfiles for each component
  - Integration with private Docker registry
  - Automated artifact handling between stages

## Results & Achievements
- Fully automated performability analysis workflow
- Modular and maintainable pipeline architecture
- Visual representation of simulation results
- Successful reproduction of FZI environment

## Future Improvements
- Branch-specific simulation configurations
- Automated trace collection integration
- Enhanced pipeline flexibility
- Expanded simulation capabilities

This project was conducted at the Institute of Information Security and Dependability (KASTEL) at KIT under the supervision of M.Sc. Sebastian Weber.
