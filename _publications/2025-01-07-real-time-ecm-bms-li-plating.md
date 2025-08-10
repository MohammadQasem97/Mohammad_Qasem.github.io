---
title: "Real-Time Electrochemical Model-Based BMS Control for Mitigating Li-Plating and Extending Battery Life"
collection: "publications"
category: "manuscripts"
permalink: "/publication/2025-01-07-real-time-ecm-bms-li-plating"
excerpt: "A simplified electrochemical Li-ion model with explicit plating/stripping dynamics is implemented on a TI TMS320F28335–based BMS and validated against a high-fidelity P2D model and experiments, enabling real-time estimation and control. The plating-aware control increases delivered capacity by ≈8.3% with <30 min added charge time and improves state-of-health by ≈17% versus CC–CV, while meeting real-time constraints."
date: "2025-01-07"
venue: "IEEE Transactions on Transportation Electrification"
paperurl: "https://ieeexplore.ieee.org/abstract/document/10835219"
doi: "10.1109/TTE.2025.3527899"
citation: "Qasem, Mohammad; Haddadin, Mariana; Yassin, Yazan; Ratrout, Sadam; Chen, Chengxiu; Stoyanov, Stoyan; Al-Hallaj, Said; Krishnamurthy, Mahesh. (2025). \"Real-Time Electrochemical Model-Based BMS Control for Mitigating Li-Plating and Extending Battery Life.\" <i>IEEE Transactions on Transportation Electrification</i>. https://doi.org/10.1109/TTE.2025.3527899."
---

This study presents a simplified electrochemical battery model incorporating side reactions for real-time (RT) applications. The proposed model is implemented on a battery management system (BMS) using the TI TMS320F28335 DSP, the model’s internal and external states are validated through extensive experimental tests against the high-fidelity P2D model by Gamma Technology. The results demonstrated the model’s ability to accurately depict the behavior of a commercially available type 21700 cylindrical cell while minimizing execution power consumption. The lithium plating/stripping model is examined and compared with the actual voltage plateau characteristics observed in practical testing. Finally, various controllers are designed and implemented into the BMS to optimize the charging current and eliminate plating without significantly increasing charging duration. The battery demonstrated an increase in capacity of 8.3% when using the proposed charging control algorithm compared with the common constant current (CC)–constant voltage (CV) technique, with a charging time increase of less than 30 min, resulting in a 17% improvement in SoH. This demonstrates the effectiveness of enhancing battery performance and longevity with minimal additional charging time.
