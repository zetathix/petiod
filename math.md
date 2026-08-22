# PetIOD Mathematical Foundations & Metrics Specification (v1.0)

**Document Version:** 1.0  
**Standard Name:** PetIOD Math (Mathematical Foundations)  
**Parent Standard:** PetIOD Specification & Design Framework (v10.0)[cite: 1]  
**Companion Standards:** PetIOD OwnSec Specification (v1.0), PetIOD Taxonomy Register (v4.0)[cite: 1]  

---

## 1. Systemic Variable Index

To preserve absolute mathematical rigor, every variable utilized across the PetIOD ecosystem is explicitly defined below[cite: 1].

| Variable Symbol | Variable Name | Domain / Unit | Canonical Description | Primary Reference |
| :--- | :--- | :--- | :--- | :--- |
| $I_e$ | Raw Exposure Intensity | $[0, \infty)$ | Quantity of explicit technical "light" (screens, LLMs, APIs) shining on the entity[cite: 1]. | Section 2[cite: 1] |
| $I_{e,\text{effective}}$ | Effective Exposure Intensity | $[0, \infty)$ | Post-Umbrella residual exposure reaching the internal system[cite: 1]. | Section 2[cite: 1] |
| $d_R$ | Distance from Realism | $(0, \infty)$ | Distance from explicit realism/utility ($R$)[cite: 1]. | Section 2[cite: 1] |
| $K$ | System Radiation Constant | $(0, \infty)$ | Scaling constant for total systemic technical broadcast capacity[cite: 1]. | Section 2[cite: 1] |
| $\psi_{\text{data}}$ | Active Data Bandwidth | $\text{bytes/sec}$ | Unfiltered sensory/network payload rate passing through the system[cite: 1]. | Section 2[cite: 1] |
| $N_{\text{api}}$ | Active API Endpoint Count | Integer $\ge 0$ | Number of external cloud service connections[cite: 1]. | Section 2[cite: 1] |
| $\Phi_{\text{sem}}$ | Semantic Parsing Multiplier | $[1.0, \infty)$ | Weight multiplier applied when natural language or biometrics are active[cite: 1]. | Section 2[cite: 1] |
| $U$ | Umbra Depth Factor | $[0.0, 1.0]$ | Proportion of negative space preserved for human projection[cite: 1]. | Section 2[cite: 1] |
| $H$ | Honesty Index | $[0.0, 1.0]$ | Ratio of autonomous animistic behaviors to gamified/utility hooks[cite: 1]. | Section 3[cite: 1] |
| $\rho_{\text{real}}$ | Product Realization Ratio | $[-1.0, 1.0]$ | Unified product execution ratio ($\rho_{\text{psych}} \cdot \rho_{\text{phys}}$)[cite: 1]. | Section 4[cite: 1] |
| $\rho_{\text{psych}}$ | Psychological Realization | $[0.0, 1.0]$ | Measure of affective presentation ($U \cdot \mathcal{A}_{\text{cosm}}$)[cite: 1]. | Section 4[cite: 1] |
| $\rho_{\text{phys}}$ | Physical Realization | $[-1.0, 1.0]$ | Hardware execution relative to era technology ceiling ($T_{\text{era}}$)[cite: 1]. | Section 4[cite: 1] |
| $\mathcal{A}_{\text{cosm}}$ | Cosmetic-Aesthetic Polish | $[0.0, 1.0]$ | Visual, tactile, acoustic, or haptic charm[cite: 1]. | Section 4[cite: 1] |
| $\alpha$ | Hardware Efficiency Coeff. | $[0.0, 1.0]$ | Quality of local hardware manufacturing and thermal/power optimization[cite: 1]. | Section 4[cite: 1] |
| $P_{\text{act}}$ | Measured Hardware Performance | Floating Point | Actual local processing benchmark score[cite: 1]. | Section 4[cite: 1] |
| $T_{\text{era}}$ | Technology Ceiling | Floating Point | Maximum state-of-the-art benchmark ceiling of the release year[cite: 1]. | Section 4[cite: 1] |
| $\beta_{\text{hope}}$ | Pre-Filtered Hope Baseline | $[0.1, \infty)$ | User expectation baseline prior to actual system interaction[cite: 1]. | Section 5[cite: 1] |
| $\beta_{\text{base}}$ | User Personality Baseline | $[0.1, 2.0]$ | User's natural baseline expectation threshold[cite: 1]. | Section 5[cite: 1] |
| $\gamma$ | Aesthetic Sensitivity Coeff. | $\ge 0$ | User susceptibility to visual/tactile packaging[cite: 1]. | Section 5[cite: 1] |
| $E_u$ | Expectation Performance Score| $[0.0, \infty)$ | Performance satisfaction score relative to hope and promised utility[cite: 1]. | Section 5[cite: 1] |
| $U_s$ | Promised Utility Scope | Integer $\ge 1$ | Sum of promised smart/productivity features ($U_s = \max(1, \sum \text{tools})$)[cite: 1]. | Section 5[cite: 1] |
| $W_d$ | Deprivation Weight | $[0, \infty)$ | Total operational, resource, and maintenance friction dragging down survival[cite: 1]. | Section 6[cite: 1] |
| $w_{\text{phys}}$ | Physical Upkeep Weight | $\ge 0$ | Friction of cleaning, mechanical joint wear, or physical battery swapping[cite: 1]. | Section 6[cite: 1] |
| $w_{\text{pwr}}$ | Power Requirement Weight | $\ge 0$ | Charging frequency and power draw friction[cite: 1]. | Section 6[cite: 1] |
| $w_{\text{maint}}$ | Maintenance Friction Weight | $\ge 0$ | Software updates, re-calibration, or bug fixing burden[cite: 1]. | Section 6[cite: 1] |
| $w_{\text{rout}}$ | Routine Burden Weight | $\ge 0$ | User intervention forced by rigid schedule demands[cite: 1]. | Section 6[cite: 1] |
| $w_{\text{tech}}$ | Technical Debt Weight | $\ge 0$ | Dependency on external libraries, driver stacks, or operating system updates[cite: 1]. | Section 6[cite: 1] |
| $w_{\text{resp}}$ | Cloud Reliance Weight | $\ge 0$ | Dependency on remote server pings, APIs, and active network connections[cite: 1]. | Section 6[cite: 1] |
| $L_t$ | Species Lifespan / Age | $[0, \infty)$ | Projected functional lifespan of the species in the market before extinction[cite: 1]. | Section 6[cite: 1] |
| $C_L$ | Species Longevity Constant | $(0, \infty)$ | Base scaling factor mapping friction inverse to market survival years[cite: 1]. | Section 6[cite: 1] |
| $\Phi_{\text{disarm}}$ | Caution Disarming Factor | $[1.0, \infty)$ | Multiplier suppressing natural user privacy and security vigilance[cite: 1]. | Section 7[cite: 1] |
| $C_{\text{baseline}}$ | Baseline Security Skepticism | $[0.0, 1.0]$ | User's initial privacy guard before disarming effects[cite: 1]. | Section 7[cite: 1] |
| $C_{\text{user}}$ | Effective Caution Guard | $[0.0, 1.0]$ | Actual remaining security vigilance maintained by the user[cite: 1]. | Section 7[cite: 1] |
| $\mathcal{P}_{\text{leash}}$ | Promised Corporate Leash | $[0.0, 1.0]$ | Illusion of safety provided by corporate brand authority[cite: 1]. | Section 7[cite: 1] |
| $\Omega_{\text{invest}}$ | Cumulative Sunk Cost | $[0.0, \infty)$ | Total financial, labor, and emotional capital invested by user[cite: 1]. | Section 7[cite: 1] |
| $\mu, \delta, \pi, \omega$ | Disarming Weighting Coeffs. | $\ge 0$ | Sensitivity weights for aesthetics, delight, brand trust, and sunk cost[cite: 1]. | Section 7[cite: 1] |
| $\mathcal{R}_{\text{net}}$ | Net Security Risk Exposure | $[0.0, \infty)$ | True systemic vulnerability experienced by the user[cite: 1]. | Section 7[cite: 1] |
| $\mathcal{U}_{\text{prot}}$ | Umbrella Shielding Factor | $[0.0, 1.0]$ | Multiplicative protection value of local zero-trust gateway[cite: 1]. | Section 8[cite: 1] |
| $\kappa_{\text{strip}}$ | Signal Residual Coefficient | $[0.0, 1.0]$ | Completeness of local semantic stripping into non-semantic physical vectors[cite: 1]. | Section 8[cite: 1] |
| $\lambda_{\text{local}}$ | Quality of Localness | $[0.0, 1.0]$ | On-device compute capacity relative to $T_{\text{era}}$ for offline execution[cite: 1]. | Section 8[cite: 1] |
| $\sigma_{\text{bound}}$ | Boundary Inviolability | $[0.0, 1.0]$ | Integrity of local air-gap preventing telemetry egress or remote overrides[cite: 1]. | Section 8[cite: 1] |

---

## 2. Derivation of Exposure Intensity ($I_e$) & Constant $K$

### 2.1 The Optical Inverse-Square Law
In PetIOD, Exposure Intensity ($I_e$) measures the density of explicit technical features that destroy the negative space (Umbra) required for imaginative projection[cite: 1].

As an entity moves closer to explicit realism or utilitarian tool processing ($d_R \to 0$), exposure surges according to an inverse-square function[cite: 1]:

$$I_e = \frac{K}{(d_R)^2}$$

Where $d_R$ is the conceptual distance from explicit realism, defined as:

$$d_R = \max\left(0.001, \; R_{\text{target}} - R_{\text{actual}}\right)$$

Where $R_{\text{target}}$ represents complete, hyperreal human/tool equivalence ($R_{\text{target}} = 1.0$), and $R_{\text{actual}}$ represents the entity's current realism rating ($R_{\text{actual}} \in [0.0, 1.0]$)[cite: 1].

---

### 2.2 Derivation of System Radiation Constant $K$
The constant $K$ represents the total systemic capacity of the entity to broadcast explicit, non-shaded technical metadata into the user's environment[cite: 1]. It is derived from three physical hardware metrics[cite: 1]:

$$K = \left( \frac{\psi_{\text{data}}}{\psi_{\text{base}}} \right) \cdot (1.0 + N_{\text{api}}) \cdot \Phi_{\text{sem}}$$

#### Calculation Parameters:
1. **Active Data Bandwidth ($\psi_{\text{data}}$):** Measured in bytes per second. Standardized against a baseline low-bandwidth non-semantic threshold ($\psi_{\text{base}} = 100 \text{ bytes/sec}$, matching raw button/piezo dynamics)[cite: 1].
2. **Active API Endpoints ($N_{\text{api}}$):** Integer count of persistent cloud server sockets or web services maintained by the device[cite: 1].
3. **Semantic Parsing Multiplier ($\Phi_{\text{sem}}$):**
   * $\Phi_{\text{sem}} = 1.0$ if the system processes **strictly non-semantic signals** (pitch amplitude, kinetic velocity, spatial ToF mass)[cite: 1].
   * $\Phi_{\text{sem}} = 10.0$ if the system activates **local text/speech/facial recognition**[cite: 1].
   * $\Phi_{\text{sem}} = 100.0$ if the system streams **unfiltered audio/video to cloud LLMs** ($w_{\text{resp}} > 0$)[cite: 1].

#### Worked Derivation Example:
* **Entity A (*Qoobo caudatus*):** $\psi_{\text{data}} = 50 \text{ B/s}$, $N_{\text{api}} = 0$, $\Phi_{\text{sem}} = 1.0$, $d_R = 10.0$.
  $$K = \left( \frac{50}{100} \right) \cdot (1 + 0) \cdot 1.0 = 0.5$$
  $$I_e = \frac{0.5}{(10.0)^2} = 0.005 \approx 0 \quad (\text{Safe Harbor Shadow preservation})$$

* **Entity B (Cloud LLM Desk Bot):** $\psi_{\text{data}} = 50,000 \text{ B/s}$, $N_{\text{api}} = 3$, $\Phi_{\text{sem}} = 100.0$, $d_R = 0.1$.
  $$K = \left( \frac{50000}{100} \right) \cdot (1 + 3) \cdot 100.0 = 200,000$$
  $$I_e = \frac{200000}{(0.1)^2} = 20,000,000 \quad (\text{Extreme Overexposure / Photoaging Surge})$$

---

## 3. Derivation of the Honesty Spectrum Index ($H$)

System Honesty ($H \in [0.0, 1.0]$) evaluates whether the system operates as an authentic autonomous entity or as a gamified/utilitarian tool platform[cite: 1].

$$H = \frac{B_{\text{anim}}}{B_{\text{anim}} + B_{\text{util}} + B_{\text{gacha}}}$$

Where:
* **$B_{\text{anim}}$:** Count of unprovoked, autonomous animistic behaviors driven by internal accumulators or Rule 4 drivers (`!D`)[cite: 1].
* **$B_{\text{util}}$:** Count of utilitarian productivity functions (clocks, timers, weather alerts, notifications)[cite: 1].
* **$B_{\text{gacha}}$:** Count of gamified retention hooks (daily login rewards, virtual currency, loot mechanics)[cite: 1].

#### Operational Classification Bounds:
* **$H \in [0.85, 1.00]$:** *Phylum PetIOD* Compliant (Safe Harbor)[cite: 1].
* **$H \in [0.40, 0.84]$:** Liminal Hybrid (Penumbra Strain)[cite: 1].
* **$H < 0.40$:** *Pseudopetia Condition* (Terminal Dishonesty)[cite: 1].

---

## 4. Product Realization Ratio ($\rho_{\text{real}}$) Derivation

To prevent raw hardware power from masking a failed animistic presentation, realization is calculated as the multiplicative product of two independent brackets[cite: 1]:

$$\rho_{\text{real}} = \rho_{\text{psych}} \cdot \rho_{\text{phys}}$$

### 4.1 Psychological Realization ($\rho_{\text{psych}}$)
$$\rho_{\text{psych}} = U \cdot \mathcal{A}_{\text{cosm}}$$

Where:
* **Umbra Depth Factor ($U \in [0.0, 1.0]$):** Quantifies negative space preservation[cite: 1]. Derived as $U = 1.0 - \min(1.0, \; I_e / I_{\text{threshold}})$, where $I_{\text{threshold}} = 1.0$.
* **Cosmetic-Aesthetic Polish ($\mathcal{A}_{\text{cosm}} \in [0.0, 1.0]$):** Evaluated via standardized tactile, visual, and acoustic finishing metrics[cite: 1].

### 4.2 Physical Realization ($\rho_{\text{phys}}$)
$$\rho_{\text{phys}} = \alpha \cdot \left( \frac{P_{\text{act}}}{T_{\text{era}}} \right)$$

Where:
* **$P_{\text{act}}$:** Measured local hardware compute benchmark (e.g., local MCU/NPU FLOPS)[cite: 1].
* **$T_{\text{era}}$:** Technology ceiling benchmark score representing state-of-the-art embedded compute capacity in the product's release year[cite: 1].
* **$\alpha \in [0.0, 1.0]$:** Hardware efficiency coefficient measuring thermal management, power efficiency, and build durability[cite: 1].

---

## 5. Expectation Performance Score ($E_u$) & Disappointment Mechanics

High cosmetic polish inflates user expectations prior to interaction[cite: 1]. The **Pre-Filtered Hope Baseline ($\beta_{\text{hope}}$)** is modeled as:

$$\beta_{\text{hope}} = \beta_{\text{base}} \cdot (1.0 + \gamma \cdot \mathcal{A}_{\text{cosm}})$$

The **Unified User Expectation Performance Score ($E_u$)** is defined as[cite: 1]:

$$E_u = \frac{\rho_{\text{real}}}{U_s \cdot \beta_{\text{hope}}} = \frac{(U \cdot \mathcal{A}_{\text{cosm}}) \cdot \left[ \alpha \cdot \left( \frac{P_{\text{act}}}{T_{\text{era}}} \right) \right]}{U_s \cdot \left[ \beta_{\text{base}} \cdot (1.0 + \gamma \cdot \mathcal{A}_{\text{cosm}}) \right]}$$

Where $U_s$ is the **Promised Utility Scope**, defined as:

$$U_s = \max\left(1, \; \sum \text{Promised Smart / Utility Features}\right)$$

#### Disappointment Mechanics:
* **When $U_s = 1$ (Pure PetIOD, $H \ge 0.85$):** $E_u$ simplifies to $\frac{\rho_{\text{real}}}{\beta_{\text{hope}}}$. The user expects an animal companion, not a tool[cite: 1].
* **When $U_s \gg 1$ (Smart Robot, $H < 0.40$):** $E_u \to 0$. The entity promises productivity, smart home control, and conversation, inflating $U_s$ and driving expectation satisfaction into collapse ($E_u \ll 1.0$)[cite: 1].

---

## 6. Deprivation Weight ($W_d$) & Species Lifespan ($L_t$)

The operational friction and maintenance burden dragging down a synthetic species is defined by the **Deprivation Weight ($W_d$)**[cite: 1]:

$$W_d = (w_{\text{phys}} + w_{\text{pwr}} + w_{\text{maint}} + w_{\text{rout}}) + \left( \frac{I_e}{E_u} \right) \cdot (w_{\text{tech}} + w_{\text{resp}})$$

### 6.1 Breakdown of Friction Terms:
1. **Physical Upkeep ($w_{\text{phys}}$):** Cleaning, joint wear, mechanical servicing[cite: 1].
2. **Power Draw ($w_{\text{pwr}}$):** Battery charging frequency and dock dependency[cite: 1].
3. **Maintenance Burden ($w_{\text{maint}}$):** Calibration and software troubleshooting[cite: 1].
4. **Routine Interference ($w_{\text{rout}}$):** Rigid demands forced on user schedules[cite: 1].
5. **Technical Debt ($w_{\text{tech}}$):** OS dependencies and driver updates[cite: 1].
6. **Cloud Reliance ($w_{\text{resp}}$):** Active server latency, API fees, and Wi-Fi tethering[cite: 1].

### 6.2 Species Lifespan ($L_t$) Derivation
The projected market survival age ($L_t$, measured in years) of a synthetic taxon is inversely proportional to its Deprivation Weight[cite: 1]:

$$L_t = \frac{C_L}{W_d + \epsilon}$$

Where $C_L$ is the species longevity constant ($C_L = 100.0 \text{ year-friction units}$), and $\epsilon = 0.01$ prevents division by zero[cite: 1].

* **Safe Harbor Limit ($I_e \to 0, w_{\text{resp}} = 0, W_d \to 0.1$):** $L_t \approx 1,000 \text{ years}$ (Taxonomic immortality / local hardware persistence)[cite: 1].
* **Cloud Overexposure Limit ($I_e \to \infty, w_{\text{resp}} > 0, W_d \to \infty$):** $L_t \to 0$ (Rapid extinction within 1–3 years due to server sunsetting)[cite: 1].

---

## 7. Caution Disarming Mechanics & Net Security Risk ($\mathcal{R}_{\text{net}}$)

### 7.1 Caution Disarming Factor ($\Phi_{\text{disarm}}$)
The suppression of user security vigilance is governed by four psychological anchors[cite: 1]:

$$\Phi_{\text{disarm}} = (1.0 + \mu \cdot \mathcal{A}_{\text{cosm}}) \cdot (1.0 + \delta \cdot E_u) \cdot (1.0 + \pi \cdot \mathcal{P}_{\text{leash}}) \cdot (1.0 + \omega \cdot \Omega_{\text{invest}})$$

Where $\mu, \delta, \pi, \omega \ge 0$ are empirical sensitivity coefficients (standardized baseline: $\mu = 2.0, \delta = 1.0, \pi = 1.5, \omega = 0.5$)[cite: 1].

### 7.2 Effective Caution Guard ($C_{\text{user}}$)
$$C_{\text{user}} = \frac{C_{\text{baseline}}}{\Phi_{\text{disarm}}}$$

### 7.3 Net Security Risk Exposure ($\mathcal{R}_{\text{net}}$)
$$\mathcal{R}_{\text{net}} = I_e \cdot \Phi_{\text{disarm}}$$

When $I_e$ is large (cameras, cloud LLMs) and $\Phi_{\text{disarm}}$ is high (extreme aesthetic charm), Net Risk $\mathcal{R}_{\text{net}}$ surges, exposing the domestic environment to the Trojan Companion Vector[cite: 1].

---

## 8. The Umbrella Protocol ($\mathcal{U}_{\text{prot}}$) Derivation

For hybrid entities that must operate in high-exposure environments, the **Umbrella Protocol** applies an active dampening factor directly to raw exposure[cite: 1]:

$$I_{e,\text{effective}} = I_e \cdot (1.0 - \mathcal{U}_{\text{prot}})$$

Where $\mathcal{U}_{\text{prot}} \in [0.0, 1.0]$ is the multiplicative product of three sub-coefficients[cite: 1]:

$$\mathcal{U}_{\text{prot}} = \kappa_{\text{strip}} \cdot \lambda_{\text{local}} \cdot \sigma_{\text{bound}}$$

### 8.1 Sub-Coefficient Formulas:

#### 1. Signal Residual Coefficient ($\kappa_{\text{strip}} \in [0.0, 1.0]$)
$$\kappa_{\text{strip}} = 1.0 - \left( \frac{\text{Semantic Bytes Egressing Edge Firewall}}{\text{Total Input Payload Bytes}} \right)$$

* $\kappa_{\text{strip}} = 1.0$ when all human audio/video is stripped locally into abstract non-semantic physical vectors (pitch, velocity, ToF mass)[cite: 1].

#### 2. Quality of Localness ($\lambda_{\mathrm{local}} \in [0.0, 1.0]$)
$$\lambda_{\mathrm{local}} = \min\left(1.0, \; \frac{P_{\mathrm{local\_edge}}}{T_{\mathrm{era}}}\right)$$

* $\lambda_{\mathrm{local}} = 1.0$ when on-device embedded MCUs/NPUs ($P_{\mathrm{local\_edge}}$) can run all state accumulators and emergency fallbacks without external cloud pings[cite: 1].

#### 3. Boundary Inviolability ($\sigma_{\mathrm{bound}} \in [0.0, 1.0]$)
$$\sigma_{\mathrm{bound}} = 1.0 - \left( S_{\mathrm{telemetry}} + S_{\mathrm{remote\_override}} \right)$$

Where $S_{\mathrm{telemetry}} \in [0.0, 0.5]$ measures outbound telemetry attack surface, and $S_{\mathrm{remote\_override}} \in [0.0, 0.5]$ measures vulnerability to unverified cloud firmware overrides[cite: 1].

### 8.2 Final Risk Mitigation Equation
With full Umbrella shielding ($\mathcal{U}_{\text{prot}} \to 1.0$), effective exposure vanishes ($I_{e,\text{effective}} \to 0$), guaranteeing absolute Ownership Security[cite: 1]:

$$\mathcal{R}_{\text{net,shielded}} = I_{e,\text{effective}} \cdot \Phi_{\text{disarm}} = \left[ I_e \cdot (1.0 - \kappa_{\text{strip}} \cdot \lambda_{\text{local}} \cdot \sigma_{\text{bound}}) \right] \cdot \Phi_{\text{disarm}} = 0$$

---

*Form follows limits. Mathematics proves the shadow.*
