# GITAM Department of Electrical, Electronics, and Communication Engineering  
GITAM School of Technology  
GITAM (Deemed to be University), Bengaluru, India  

---

## Extended Abstract PROJ3999 (Major Project)  

*Title*: Channel Estimation with Interference in OFDM Modulation using GNU Radio  
*Project Supervisor*: Ramesha M  
*Cluster Name*: Communication  
*Project Coordinator*: Ambar Bajpai  

---

### Mini Project (PROJ2999) Outcome  

- Developed an OFDM transceiver using GNU Radio and Software-Defined Radio (SDR), enabling robust digital communication.  
- Successfully implemented real-time transmission and reception of signals with effective synchronization and channel estimation techniques.  
- Demonstrated system robustness by analyzing performance metrics such as Bit Error Rate (BER) and Signal-to-Noise Ratio (SNR) under various channel conditions.  
- Explored and implemented PAPR reduction methods to improve signal transmission efficiency.  
- Utilized open-source tools for cost-effective and flexible prototyping of communication systems, paving the way for future research in advanced wireless communication.  

---

### Extended Project Abstract  

OFDM is a prominent modulation scheme for modern wireless communication systems due to its high spectral efficiency and resistance to multipath fading. However, real wireless channel signals are often interfered with by nearby signals and noise, complicating accurate channel estimation—a critical stage for maintaining OFDM integrity.  

This research utilizes GNU Radio, an open-source software-defined radio platform, to investigate channel estimation under interference. It examines the effects of interference on pilot-based channel estimation techniques, including Least Squares (LS) and Minimum Mean Square Error (MMSE) estimators.  

Through simulation and real-time operation, the study evaluates the impact of co-channel and adjacent channel interference. The experimental setup leverages GNU Radio's versatility for OFDM system realization, interference injection, and self-developed algorithms for interference mitigation.  

Key performance parameters—BER, MSE of channel estimation, and SNR—are analyzed under low-SNR conditions. Results highlight interference degradation on channel estimation accuracy and demonstrate improvements using filtering and interpolation algorithms.  

This study provides insights into robust OFDM systems operating in high-interference scenarios, contributing to advancements in 5G and future wireless communication systems. It emphasizes the importance of effective channel estimation and explores various interference cancellation methods within the GNU Radio framework.  

---

### Extended Project Objectives  

1. *Develop and Implement Channel Estimation Techniques*: Create pilot-based estimation methods such as LS and MMSE for OFDM using GNU Radio.  
2. *Analyze the Impact of Interference*: Assess co-channel and adjacent channel interference on estimation accuracy and overall system performance.  
3. *Propose and Test Mitigation Strategies*: Design methods for interference filtering and improved channel estimation in interference-prone environments.  
4. *Assess System Performance*: Measure effectiveness using BER, MSE, and SNR under different interference scenarios.  

---

### Gantt Chart for Extended Project PROJ3999  

| Week    | Task                                           |
|---------|------------------------------------------------|
| 1–2     | Project Planning and Setup                    |
| 3–4     | Literature Review and Research                |
| 5–6     | System Design in GNU Radio                    |
| 7–8     | Interference Modeling                         |
| 9–10    | Implementation of Estimation Techniques       |
| 11–12   | Testing and Interference Mitigation           |
| 13–14   | Performance Analysis                          |
| 15–16   | Documentation and Reporting                   |

---

### Suggested IEEE Conference Targets  

- *IEEE International Conference on Communications (ICC) 2025*  
- *IEEE Global Communications Conference (GLOBECOM) 2025*  

---

### Group Details  

- *Haripriya Rao M* (BU21EECE0100567)  
- *Kiran PS* (BU21EECE0100564)  
- *Hamsini Reddy KS* (BU21EECE0100546)
