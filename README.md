# optimal-measurement-selection-for-voltage-monitoring
This repository contains all the code and data used for the numerical results in the paper "Optimal Measurement Selection for Certifiable Voltage Monitoring in Power Distribution Systems", published in HICSS 2027

Authors: Peng Zhang, Line A. Roald, and Manish K. Singh

University of Wisconsin-Madison

# Motivation and Main Results
Maintaining consumer-end voltages within mandated limits is a central task in operating power distribution systems. Rising penetration of distributed generation, electric vehicles, and flexible loads complicates this task, while a scarcity of real-time measurements leaves distribution networks largely unobservable. Operators commonly monitor a few bellwether meters, which indicate operational health but certify nothing about the unmeasured buses. This work asks how to select measurements that are reported in real time and can certify network-wide voltage-limit compliance. 

We first illustrate the geometry of the measurement values that certify voltage safety at unmeasured nodes. Building on this geometry, we formulate a bilevel optimization that selects measurements to maximize certification capability, introducing a novel safety-violation metric with favorable monotonicity properties. We derive a strong-duality-based single-level reformulation and two scenario-reduction schemes with quantifiable suboptimality. Numerical tests on the SCE 56-bus system corroborate the superior certification capability and computational efficiency of the proposed approach.
