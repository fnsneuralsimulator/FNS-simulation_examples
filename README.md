# FNS-simulation_examples

Through the folder 'single_node' you will be able to reproduce the activity within a single node.
In order to obtain the .CSVs of the model activity (firing.CSV and burning.CSV) in the folder FNS/single_node/output, you can use the following "experiment command":

> .\start.bat single_node -M

--

Through the folder 'resonance_pair' you will be able to reproduce the Resonance Pair mechanism, as described in the paper of:
- Maslennikov and Nekorkin, 2014. Modular networks with delayed coupling: Synchronization and frequency control. Phys. Rev. E 90.
- Gollo, L. et al., 2014. Mechanisms of zero-lag synchronization in cortical motifs. PLOS computational biology 10 (4), 1–17)
In order to obtain the .CSVs of the model activity (firing.CSV and burning.CSV) in the folder FNS/resonance_pair/output, you can use the following "experiment command":

> .\start.bat resonance_pair -M

--

Through the folder 'dynamical_relaying' you will be able to reproduce the Dynamical Relaying mechanism, as described in the paper of Vicente et al., 2008: "Dynamical relaying can yield zero time lag neuronal synchrony despite long conduction delays".
In order to obtain the .CSVs of the model activity (firing.CSV and burning.CSV) in the folder FNS/dynamical_relaying/output, you can use the following "experiment command":

> .\start.bat dynamical_relaying -M

--

Through the folder 'connectivity_14' you will be able to simulate the Default Mode Network (composed of 14 regions) of a real subject, described in the paper "FNS: an event-driven spiking neural network based on the LIFL model" (in review).
In order to obtain the .CSVs of the model activity (firing.CSV and burning.CSV) in the folder FNS/connectivity_14/output, you can use the following "experiment command":

> .\start.bat connectivity_14 -M

In order to run this model the user should have to increase the heap size. Please refer to the user manual for the instructions.

--

Please read the user manual for additional information: https://docs.google.com/document/d/1-oJK6dzu6KIggYonajqVq8xA6mUZ3ZZdBMq7zVMyTcA/export?format=pdf
