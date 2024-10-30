# Monitoring and Surveillance of Genetically Engineered Microorganisms
A finite automata-based project for tracking and regulating the behavior of genetically engineered microorganisms in real-world environments.

# Project Overview
Objective: Implement a monitoring and alert system to detect unusual behavior in genetically engineered microorganisms, ensuring safe environmental release.
Solution: Uses finite automata (FA) to monitor growth patterns and trigger alerts based on deviations.
Features
Real-time Surveillance: Continuous monitoring of microorganism growth patterns.
Finite Automata Logic: DFA designed to identify normal vs. unusual growth.
Alerts: Automatic alerts upon detecting abnormal patterns.
Modular States:
Start: Initial observation state.
Normal Growth: Expected behavior.
Unusual Activity (Early & Persistent): Detects early unusual patterns and tracks persistent ones.
Alert: Final state for critical conditions.
