# RESEARCH STATEMENT
**Shenyu Liu, Ph.D.**

## Research Overview & Philosophy
Modern engineering systems—ranging from autonomous vehicles and multi-agent robotics to smart cyber-physical infrastructure—increasingly exhibit intertwined continuous dynamics and discrete events. The framework of **switched and hybrid systems** provides a rigorous mathematical foundation to address these complex behaviors. Across my academic career—from my doctoral work at the University of Illinois Urbana-Champaign (UIUC) to my postdoctoral research at UC San Diego (UCSD) and my faculty appointment at Beijing Institute of Technology (BIT)—my research has focused on the **fundamental stability analysis, data-driven control, and resilient algorithm design for switched and hybrid systems**. 

My research vision bridges deep theoretical foundations with real-world engineering scalability, addressing core questions in nonlinear stability, stochastic hybrid modeling, cyber-security, and large-scale computation.

---

## Key Research Accomplishments

### 1. Stability Analysis for Deterministic Switched Nonlinear Systems
Standard stability results for switched nonlinear systems rely on Average Dwell-Time (ADT) or Average Activation-Time (AAT) conditions. However, conventional methodologies assume linear supply functions within multiple Lyapunov function frameworks—an assumption that fails for nonlinear supply functions, such as those present in **integral Input-to-State Stability (iISS)**. My research resolves key open questions in this domain:
* **Quasi/Practical Stability Extensions:** I introduced modified notions of "quasi-" and "practical-" ISS/iISS, establishing explicit sufficient conditions for switched nonlinear systems operating under non-standard dynamics (*IEEE TAC, 2021*).
* **Nonlinear Lyapunov Scaling:** By designing novel hybrid Lyapunov function scalings, I developed conditions ensuring uniform (i)ISS across ADT/AAT switching signals with nonlinear supply functions (*Math. Control Signals Systems, 2022*).
* **Impulsive & Functional Inequalities:** Utilizing a hybrid systems framework, I established unified stability criteria governed by functional inequalities, accommodating complex impulsive switching behavior (*Automatica, 2025*).

### 2. Stability Analysis for Stochastic & Semi-Markovian Switched Systems
For stochastic systems, almost sure Global Asymptotic Stability (GAS) fails to capture transient state distributions or finite-time statistical behavior. To overcome this:
* **Non-Conservative Moment Stability:** By integrating conditional renewal equations, I developed novel criteria for the asymptotic moment stability of semi-Markovian switched systems (*SIAM J. Control Optim., 2024*).
* **Time-Delay System Duality:** I proved that asymptotic moment stability in semi-Markovian processes can be mapped to the GAS of an auxiliary linear time-delay system, where system memory is explicitly captured by time delay—yielding significantly tighter, non-conservative bounds (*SIAM J. Control Optim., 2024; Systems & Control Letters, 2024*).

### 3. Switched Control Design, Cyber-Physical Security, & Distributed Optimization
In addition to foundational theory, I actively engineer switched control strategies to solve open problems in security and large-scale computation:
* **Cyber-Physical Security & Resilient Control:** I formulated a game-theoretic switching defense mechanism against adversarial attacks on linear systems. By partitioning potential attack profiles and applying a Lyapunov-guided switching rule, the defender guarantees system stability under dwell-time constraints (*IEEE TAC, 2023*).
* **Data-Driven Control of Unknown Switched Systems:** I developed a two-phase data-driven control framework introducing a novel set-membership approach for mode detection, bypassing the need for full identification before stabilization (*IEEE TAC, 2025*).
* **Uniting Control:** Leveraging hybrid system theory, I designed unified control laws that ensure ISS under persistent external disturbances, permitting dynamic switching between local high-performance and global stabilizing controllers (*Automatica, 2024*).

---

## Future Research Directions

Supported by my ongoing **National Natural Science Foundation of China (NSFC Grant No. 62203053)** project, my future research program will focus on four interconnected frontiers:

* **1. Theoretical Foundations — Converse Theorems & All-Unstable Subsystems:**
  I aim to characterize necessary and sufficient Lyapunov conditions for uniform (i)ISS over restricted switching classes. Furthermore, I will extend my framework to stabilize systems composed entirely of unstable subsystems.

* **2. Stochastic Hybrid Diffusions & Unified Theories:**
  I plan to generalize my moment stability criteria to stochastic hybrid diffusions and formulate a single, unified mathematical structure uniting deterministic and stochastic switching signal analysis.

* **3. Scalable Distributed Optimization — Switched Data Transmission:**
  To support large-scale neural network training and distributed optimization, I am developing switched transmission algorithms synchronized with consensus protocols to solve large-scale linear algebraic equations (LAE) under severe bandwidth limits.

* **4. Cyber-Physical Security & Data-Driven Control Frameworks:**
  I will expand my data-driven mode-detection algorithms to real-time, resource-constrained autonomous agents operating in dynamic, unmodeled environments.

---

## Key Selected References
1. **S. Liu**, A. Russo, D. Liberzon, A. Cavallo. *IEEE Trans. Autom. Control*, 67(11): 5841-5855, 2021.
2. **S. Liu**, A. Tanwani, D. Liberzon. *Math. Control Signals Systems*, 34: 297–327, 2022.
3. **S. Liu**, S. Martinez, J. Cortes. *IEEE Trans. Autom. Control*, 68(12): 7326-7341, 2023.
4. **S. Liu**, P. Wen. *SIAM J. Control Optim.*, 62(3): 1783-1808, 2024.
5. **S. Liu**, A. Tanwani. *Automatica*, 171: 111928, 2025.
6. **J. Eising, S. Liu**, S. Martinez, J. Cortes. *IEEE Trans. Autom. Control*, 70(6): 3830-3845, 2025.