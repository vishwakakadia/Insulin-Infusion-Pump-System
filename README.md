# Insulin-Infusion-Pump-System
Safety Critical System for infusion insulin system

For the insulin-Glucagon Infusion pump system,I used Unified process mode for creating simulation(Using Matlab).This is work based on the dynamic approach. The overall approach for the insulin Glucagon infusion system is that data fetch manually and process the data using Bergman mathematical model. And it gives you visual interpretation of glucose and insulin rate that how much glucose in the patients body and how much we have to inject as an insulin. There are two conditions like if patients glucose level is less then 80 its called Hypoglycemia at that time alarm gives an alert and stop the process. after that gives the suggestion of food intake and medicine so this is the not that much critical phase so its handle by the internal staff. second condition is that glucose level is more then 180 its called Hyperglycemia. In this situation system immediately stop and gives an alert to called a doctor. This situation is really critical so its only handle by the professionals. In every time interval data will be automatically measured.

## 1. Mathematical Model


The Bergman minimal model can be represented mathematically using
a set of differential equations. Here is a simplified mathematical represen-
tation of the Bergman model for insulin and glucose dynamics

![glucose equation](https://github.com/vishwakakadia/Insulin-Infusion-Pump-System/blob/main/glucose.png)

where: G(t) represents the concentration of glucose in the blood at time
I(t) represents the concentration of insulin in the blood at time t.
X(t) represents the insulin sensitivity at time t.
Ra(t) represents the rate of appearance of glucose in the blood at time
t.
k1, k2, and k3 are model parameters that influence the glucose dynamics.

![insulin equation](https://github.com/vishwakakadia/Insulin-Infusion-Pump-System/blob/main/insulin.png)

where: dI(t)/dt represents the rate of change of insulin concentration
over time.
k4, k5, and k6 are model parameters that influence the insulin dynamics.
These differential equations describe the rates of change of glucose and
insulin concentrations in the bloodstream. The terms on the right-hand
side of the equations represent various processes such as glucose uptake,
insulin secretion, insulin action, and glucose production.

## 2. Hazard Analysis
### 2.1 Systems Theoretic Process Analysis (STPA)
<img src="https://github.com/vishwakakadia/Insulin-Infusion-Pump-System/blob/main/stpa.png" alt="STPA" width="700" height="500">

### 2.2 Failure Modes and Effects Analysis (FMEA)

<img src="https://github.com/vishwakakadia/Insulin-Infusion-Pump-System/blob/main/fmea.png" alt="STPA" width="700" height="400">

## 3. Safety Plan

1. **Identify and Address Potential Risks:**
   - Analyze where, when, how, and why the problems occur, and with which medications.

2. **Maintenance of System and Equipment:**
   - Monitor the system’s performance.
   - Gather feedback from users and healthcare professionals.

3. **Alarm Management and Monitoring:**
   - Double check infusion rate, medication, and dosage.

4. **Staff Training:**
   - Create user manuals and guidelines.

5. **Continuously Improve Quality:**
   - Improve by collecting feedback, conducting research, and staying updated with industry standards and regulations.

## 4. Prototypes
<img src="https://github.com/vishwakakadia/Insulin-Infusion-Pump-System/blob/main/systemoverview.jpg" alt="STPA" width="700" height="300">
<img src="https://github.com/vishwakakadia/Insulin-Infusion-Pump-System/blob/main/measurementhistory.jpg" alt="STPA" width="700" height="300">



