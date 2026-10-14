
# [ClearTurn] An Adaptive Voice + Visual Highway Navigation HMI

**Personal Automotive UX Concept + 3D Design Project | Aug. 2026 - Oct. 2026**

**Designed and developed by:** Lukman Adeyemi  
**Role:** UX/UI Designer & 3D Interaction Designer  

---

### 📖 UX Case Study Overview

This case study documents the design and development of **ClearTurn**, a personal automotive UX concept inspired by a real highway driving experience in Michigan. 

The case study covers the **project inspiration, problem identification, human-centered design approach, and adaptive navigation strategy**, including five navigation stages: **Cruise → Prepare → Approach → Decision → Cruise**. It also demonstrates how 2D interface concepts were integrated into a 3D vehicle interior using **Figma, Stitch AI, and Blender**, with coordinated visual and voice guidance.

Finally, the case study reflects on **lessons learned, project limitations, and opportunities for future improvements**, including interactive navigation, enhanced 3D modeling, usability testing, and personalization.

---
## 🎬 3D Video Demonstration

### ▶️ [Watch the ClearTurn 3D Automotive HMI Prototype](https://drive.google.com/file/d/143ysiMyBbOyITd-eDN69yIRz9erDiyrt/view?usp=drive_link)

The video demonstrates ClearTurn's adaptive navigation concept within a 3D vehicle interior, showcasing the transition between navigation states and the coordination of visual information with voice guidance.

---
https://github.com/user-attachments/assets/1d84dae3-3d7c-4f39-8778-dc3d14f815b9

## About

ClearTurn is a human-centered automotive navigation HMI (Human-Machine Interface) concept designed to explore how drivers can receive clearer highway navigation instructions while reducing the need for repeated visual checking.

The project combines 2D interface design, 3D automotive visualization, and voice-guided navigation to demonstrate an adaptive navigation experience.

---

## 🛠️ Design Tools

### Blender — 3D Automotive Visualization

Used to develop and present the conceptual vehicle interior, integrate the navigation interface into the dashboard display, configure camera perspectives, and produce the animated 3D demonstration.

### Figma — UI/UX Design

Used as part of the 2D interface design and prototyping workflow.

### Stitch AI — Interface Design Exploration

Used to support visual interface exploration and design development.

### Additional Design Methods

- Human-Centered Design
- Automotive HMI Concepts
- Information Hierarchy
- Interaction Design
- Digital Prototyping
- 2D-to-3D Interface Integration
- Contextual Navigation Guidance
- Multimodal Interaction

---

## Project Inspiration

During a recent long-distance drive from Dearborn to Grand Rapids, Michigan, I relied on the vehicle's navigation display throughout the trip. Although the navigation was helpful, I noticed myself repeatedly looking at the screen to monitor how much distance remained.

Highway interchanges also required additional attention. When approaching exits or road splits, determining whether to take an exit or remain on the highway could become confusing, particularly when traveling an unfamiliar route.

This experience led me to explore a question:

**How might an automotive navigation system communicate trip progress and highway decisions more clearly while reducing the need for repeated visual checking?**

---

## Problem 1 - Repeated distance checking

On a long highway segment, a driver may repeatedly look at the screen:

**150 mi → 140 mi → 130 mi → 120 mi...**

ClearTurn explores whether configurable spoken progress updates could provide that information without requiring another visual check.

---
## Problem 2 - Highway decision uncertainty

At an unfamiliar interchange, the driver needs to quickly understand:

Do I take this exit?  
Do I stay on the highway?  
Which lane should I be in?

ClearTurn explores explicit correct-route + incorrect-route communication.

For example:

- ✅ **KEEP LEFT**
  
versus

- ❌ **DO NOT TAKE EXIT 8**

---

## ClearTurn Adaptive Navigation Strategy

ClearTurn changes the amount and prominence of navigation information according to how urgently the driver needs to make a decision.

**CRUISE → PREPARE → APPROACH → DECISION → CRUISE**


### ✅ Stage 1 →  CRUISE

**No immediate maneuver**

*Minimal information*

**Design Objective:** Maintain trip awareness without presenting unnecessary navigation details.


<img width="1672" height="905" alt="Cruise" src="https://github.com/user-attachments/assets/a3fd6251-b037-473c-a442-4ca2757fe2cf" />
 

When no immediate maneuver is required, ClearTurn reduces information density and prioritizes only the driver's current route, destination, remaining distance, estimated arrival, and next important maneuver.

The interface remains visually quiet until an upcoming highway decision requires additional attention.

**Primary action:** CONTINUE ON I-96 W

**Trip awareness:** Grand Rapids · 120 mi · ETA 4:38 PM

**Voice assistance:** “Continue on I-96 West toward Grand Rapids.”

---

### ✅ Stage 2 → PREPARE

**5 miles before decision**

*Upcoming maneuver introduced*

**Design Objective:** Provide early awareness of an upcoming highway decision.

<img width="1672" height="911" alt="Prepare" src="https://github.com/user-attachments/assets/003624ef-893b-400f-a46a-b47db0066a9f" />
 

As the vehicle approaches an important highway decision, ClearTurn transitions from the calm Cruise interface to a closer road view. At five miles, the system introduces the upcoming maneuver without overwhelming the driver with detailed lane instructions.

**Primary action:** PREPARE TO KEEP LEFT

**Visual change:** Map zooms toward the upcoming highway interchange

**Voice assistance:** “In five miles, prepare to keep left to remain on I-96 West.”

---

### ✅ Stage 3 → APPROACH

**2 miles before decision**

*Lane guidance emphasized*

**Design Objective:** Communicate the correct lane and route before reaching the highway split.


 <img width="1672" height="911" alt="Approach" src="https://github.com/user-attachments/assets/42d48535-a791-4346-96f3-8b4bbfccc9fe" />


At two miles from the highway split, ClearTurn increases guidance by introducing lane-level direction while keeping the interface focused on the driver's immediate decision.

**Primary action:** KEEP LEFT

**Visual guidance:** Blue route and directional arrows identify the lanes that continue on I-96 W

**Voice assistance:** “In two miles, keep left to remain on I-96 West.”

---

### ✅ Stage 4 → DECISION

**At highway split**

*Maximum directional clarity*

**Design Objective:** Make the correct highway decision explicit at the point where directional clarity is most important.

 <img width="1672" height="911" alt="Decision" src="https://github.com/user-attachments/assets/342fa361-a58f-4a49-be83-f9b181f44528" />


At the highway split, ClearTurn shifts to its highest level of guidance. The correct route remains highlighted in blue while repeated red X markers identify the exit the driver should avoid.

**Primary action:** KEEP LEFT

**Visual guidance:** Blue route = continue on I-96 W; red X markers = do not enter Exit 8

**Voice assistance:** “Keep left! Do not take Exit 8, Continue on I-96 West.”

---

### ✅ Stage 5  → CRUISE

**Maneuver completed**

*Interface becomes calm again*

**Design Objective:** Confirm the completed maneuver and return the interface to normal highway navigation.

<img width="1672" height="920" alt="Route Correct on I-96 West" src="https://github.com/user-attachments/assets/4557c0e9-412e-4336-811b-4219c68046ef" />


After the highway decision is completed correctly, ClearTurn confirms the route and immediately reduces information intensity, returning the driver to a calm highway navigation state.

**Primary action:** ROUTE CORRECT — CONTINUE ON I-96 W

**Visual guidance:** Exit warnings and lane-level guidance disappear as the blue route returns to normal cruise guidance

**Voice assistance:** “Your Route is correct, Continue on I-96 West toward Grand Rapids.”

- “This design was created by Lukman Adeyemi”

---

## Lessons Learned, Limitations & Future Improvements

### Lessons Learned

Developing ClearTurn strengthened my understanding of how human-centered design principles can be translated from 2D interface concepts into a 3D automotive environment.

- **Context-aware design:** I learned the importance of adapting information hierarchy to the driver's immediate needs, providing minimal guidance during normal highway travel and more prominent instructions at critical decision points.

- **2D-to-3D integration:** Using Figma, Stitch AI, and Blender expanded my practical understanding of 3D visualization, spatial layout, camera positioning, and integrating digital interfaces into a vehicle interior.

- **Multimodal interaction:** Combining visual instructions with voice guidance highlighted the importance of coordinating different communication methods to create a consistent navigation experience.

### Project Limitations

ClearTurn is an exploratory design prototype rather than a fully functional automotive navigation system.

- **Conceptual simulation:** The navigation scenarios are predefined and do not respond dynamically to real-time vehicle location, traffic conditions, or driver behavior.

- **Simplified vehicle interior:** The 3D environment focuses on demonstrating the navigation experience rather than representing a production-ready automotive interior.

- **Limited validation:** The proposed benefits of reducing unnecessary screen checking and improving highway decision clarity have not yet been evaluated through controlled usability testing or driving simulations.

### Future Improvements

The next phase of ClearTurn would focus on improving interactivity, realism, and evidence-based design validation.

- **Interactive navigation:** Develop a functional prototype capable of adapting visual and voice guidance to changing route conditions.

- **Enhanced 3D modeling:** Refine vehicle interior proportions, materials, lighting, and display placement to create a more realistic automotive experience.

- **User testing:** Conduct usability studies or simulated driving evaluations to assess glance behavior, instruction comprehension, cognitive workload, and driver confidence.

- **Personalization:** Explore configurable voice-update intervals and accessibility preferences to accommodate different driver needs.

---
### Key Takeaway

ClearTurn reinforced my understanding that effective automotive interface design is not simply about presenting more information, but about delivering the right information, at the right moment, in a form that supports clear and confident decisions.

This project represents my continued development in UX/UI design, automotive HMI concepts, 3D visualization, and digital prototyping.

---

## 📺 Project Demonstration

**[▶️ Watch ClearTurn — 3D Automotive Navigation HMI](https://drive.google.com/file/d/143ysiMyBbOyITd-eDN69yIRz9erDiyrt/view?usp=drive_link)**

https://github.com/user-attachments/assets/1d84dae3-3d7c-4f39-8778-dc3d14f815b9

---

## 👨‍💻 Project Author

**Lukman Adeyemi**  
UX/UI Design | 3D Visualization | Human-Centered Design

- **Email:** [Lukman.adeyemi05@gmail.com](mailto:Lukman.adeyemi05@gmail.com)
- **LinkedIn:** [linkedin.com/in/lukman-adeyemi0512](https://www.linkedin.com/in/lukman-adeyemi0512/)
- **GitHub:** [github.com/lukmanasquare](https://github.com/lukmanasquare)

---

*ClearTurn is an independent personal design concept created for portfolio demonstration and design exploration.*
