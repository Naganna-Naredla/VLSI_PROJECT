Memristor-Based VLSI Circuit Design Project

Project Title

Design and Implementation of Memristor-Based Filters, Logic Gates, and SRAM for Advanced Circuit Applications

Project Overview

This project investigates the use of memristors in circuit design, particularly in the implementation of:

Low-pass and high-pass filters

Digital logic gates (AND, OR, NAND, NOR, etc.)

SRAM circuits with read and write operations

The circuits were designed and simulated in LTSpice, utilizing the unique resistance-switching characteristics of memristors. The study also explored pulse-based read and write operations in SRAM circuits.

Key Features

Memristor Modeling: Custom memristor models were used in LTSpice.

Filter Design: Implemented low-pass, high-pass, band-pass, and band-stop filters.

Logic Gates: Designed basic digital logic gates using memristors.

SRAM Circuit: Implemented a memristor-based SRAM with read and write operations.

Pulse-Based Operations: Evaluated control signals (READ, WRITE, COMB) for memory operations.

Graphical Analysis: Voltage signals were analyzed and compared with theoretical models.

Methodology

1. Simulation Setup

Memristor Model: Created and tested in LTSpice.

Circuit Configuration: Memristors were connected in SRAM circuits, with voltage sources managing read and write operations.

2. SRAM Circuit Design

Write Operation

Utilizes MOSFETs and voltage sources.

Write is enabled when WRITE = High (Vdd) and READ = Low (0V).

COMB signal manages voltage transitions.

LTSpice graphs validate write operation.

Read Operation

Similar to write operation but toggles signals.

Read is enabled when READ = High (Vdd) and WRITE = Low (0V).

COMB signal ensures correct voltage levels.

Graphs show expected signal transitions.

3. Filter and Logic Gate Design

Filters: Implemented and tested in LTSpice.

Logic Gates: Basic gates designed with memristors and voltage-controlled switching.

Results & Observations

The memristor-based filters effectively performed frequency-based signal processing.

Logic gates operated as expected, showcasing memristor-based digital circuit feasibility.

SRAM read and write operations demonstrated functional memory behavior.

Graphical comparisons validated simulation results against theoretical models.

Conclusion

This project successfully demonstrates the potential of memristors in VLSI circuit design. The implementation of filters, logic gates, and SRAM highlights their efficiency in both analog and digital applications. Future research should focus on optimizing these designs for fabrication and scaling to more complex circuits.

Tools & Technologies Used

LTSpice – Circuit design and simulation

Memristor Models – Custom modeling for accurate simulations

MOSFETs & Voltage Sources – Used in SRAM and logic gates

Future Work

Enhancing the reliability of memristor-based memory circuits.

Exploring new circuit architectures with memristors.

Investigating fabrication techniques for practical implementation.

Acknowledgments

This project was developed as part of the VLSI course and contributes to the research on memristor-based circuit design.
