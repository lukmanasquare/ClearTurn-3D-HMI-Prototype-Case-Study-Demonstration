
# [ClearTurn] "An Adaptive Voice + Visual Highway Navigation HMI"

**Personal Automotive UX Concept + 3D Design Project | Aug. 2026 - Oct. 2026**

**Designed and developed by:** Lukman Adeyemi  
**Role:** UX/UI Designer & 3D Interaction Designer  
**Design Tools:** Blender, Figma, Stitch AI

---

## 🎬 3D Video Demonstration

### ▶️ [Watch the ClearTurn 3D Automotive HMI Prototype](https://drive.google.com/file/d/143ysiMyBbOyITd-eDN69yIRz9erDiyrt/view?usp=drive_link)

The video demonstrates ClearTurn's adaptive navigation concept within a 3D vehicle interior, showcasing the transition between navigation states and the coordination of visual information with voice guidance.

**[View Full 3D Prototype Video](https://drive.google.com/file/d/143ysiMyBbOyITd-eDN69yIRz9erDiyrt/view?usp=drive_link)**



https://github.com/user-attachments/assets/1d84dae3-3d7c-4f39-8778-dc3d14f815b9
---

## About

ClearTurn is a human-centered automotive navigation HMI (Human-Machine Interface) concept designed to explore how drivers can receive clearer highway navigation instructions while reducing the need for repeated visual checking.

The project combines 2D interface design, 3D automotive visualization, and voice-guided navigation to demonstrate an adaptive navigation experience.

The concept is illustrated through a simulated journey from Dearborn to Grand Rapids, Michigan, using Interstate 96 West.

### ✅ Description and Purpose

ClearTurn explores two common challenges encountered during long-distance highway travel:

1. Repeatedly checking the navigation display to monitor remaining travel distance.
2. Uncertainty when approaching unfamiliar highway interchanges, exits, and lane splits.

The proposed solution uses contextual information hierarchy to adjust the prominence of navigation instructions according to the driver's immediate decision-making needs.

During normal highway travel, the interface remains visually calm. As an important highway decision approaches, the system progressively introduces more prominent route guidance, lane instructions, and voice assistance.

After the maneuver is completed, the interface returns to a less demanding navigation state.

**Project Goal:** Explore how adaptive visual and voice-guided navigation can communicate trip progress and highway decisions more clearly while minimizing unnecessary visual information.

---

## 💡 Project Inspiration

During a long-distance drive from Dearborn to Grand Rapids, Michigan, I relied on the vehicle's navigation display throughout the trip.

Although the navigation system was helpful, I noticed myself repeatedly looking at the screen to monitor how much distance remained.

Highway interchanges also required additional attention. When approaching unfamiliar exits or road splits, determining whether to take an exit or remain on the highway could become confusing.

This experience inspired the following design question:

> **How might an automotive navigation system communicate trip progress and highway decisions more clearly while reducing the need for repeated visual checking?**

ClearTurn was developed as a conceptual response to this question.

---

## 🎯 Design Problems

### Problem 1 — Repeated Distance Checking

During long-distance travel, drivers may repeatedly check the navigation display to monitor remaining distance.

For example:

**150 mi → 140 mi → 130 mi → 120 mi**

ClearTurn explores the use of configurable spoken progress updates to communicate trip information without requiring another visual check.

### Problem 2 — Highway Decision Uncertainty

At unfamiliar highway interchanges, drivers need to quickly understand:

- Do I take this exit?
- Do I stay on the highway?
- Which lane should I be in?

ClearTurn explores explicit communication of both the correct route and the route to avoid.

For example:

- ✅ **KEEP LEFT**
- ❌ **DO NOT TAKE EXIT 8**

The concept combines directional guidance, visual highlighting, and voice instructions to make the intended maneuver more explicit.

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

## 🚘 ClearTurn Adaptive Navigation Strategy

ClearTurn changes the amount and prominence of navigation information according to how urgently the driver needs to make a decision.

### Navigation Sequence

**CRUISE → PREPARE → APPROACH → DECISION → CRUISE**

The following sections explain the five navigation states demonstrated in the project.

---

## Navigation Experience

### ✅ Stage 1 — CRUISE: Minimal Information

**Scenario:** No immediate highway maneuver is required.

During normal highway travel, ClearTurn reduces information density and prioritizes the driver's current route, destination, remaining distance, estimated arrival time, and next important maneuver.

The interface remains visually calm until an upcoming highway decision requires additional attention.

**Interface Information:**
- Primary Action: **CONTINUE ON I-96 W**
- Destination: Grand Rapids, Michigan
- Distance Remaining: 120 miles
- Estimated Arrival: 4:38 PM
- Next Important Maneuver: 84 miles

**Voice Assistance:**

> "Continue on I-96 West toward Grand Rapids."

**Design Objective:** Maintain trip awareness without presenting unnecessary navigation details.

<!-- Optional: Add Cruise interface screenshot here -->
<!-- ![ClearTurn Cruise Interface](images/cruise.png) -->

---

### ✅ Stage 2 — PREPARE: Upcoming Maneuver Awareness

**Scenario:** Five miles before an important highway decision.

As the vehicle approaches a highway interchange, ClearTurn transitions from the calm Cruise interface to a closer road view.

At five miles, the system introduces the upcoming maneuver without overwhelming the driver with detailed lane instructions.

**Interface Information:**
- Primary Action: **PREPARE TO KEEP LEFT**
- Upcoming Maneuver: 5 miles
- Visual Change: Map zooms toward the highway interchange
- Destination: Grand Rapids, Michigan

**Voice Assistance:**

> "In five miles, prepare to keep left to remain on I-96 West."

**Design Objective:** Provide early awareness of an upcoming highway decision.

<!-- Optional: Add Prepare interface screenshot here -->
<!-- ![ClearTurn Prepare Interface](images/prepare.png) -->

---

### ✅ Stage 3 — APPROACH: Lane Guidance

**Scenario:** Two miles before the highway split.

As the vehicle approaches the interchange, ClearTurn increases the prominence of navigation guidance.

The interface introduces lane-level direction while keeping the driver's immediate decision as the primary focus.

**Interface Information:**
- Primary Action: **KEEP LEFT**
- Upcoming Maneuver: 2 miles
- Correct Route: I-96 West
- Visual Guidance: Blue route highlighting and directional arrows

**Voice Assistance:**

> "In two miles, keep left to remain on I-96 West."

**Design Objective:** Communicate the correct lane and route before reaching the highway split.

<!-- Optional: Add Approach interface screenshot here -->
<!-- ![ClearTurn Approach Interface](images/approach.png) -->

---

### ✅ Stage 4 — DECISION: Maximum Directional Clarity

**Scenario:** The vehicle reaches the highway split.

At the decision point, ClearTurn shifts to its highest level of navigation guidance.

The correct route remains highlighted in blue, while red X markers identify the exit the driver should avoid.

**Interface Information:**
- Primary Action: **KEEP LEFT**
- Correct Route: Continue on I-96 West
- Incorrect Route: Exit 8 toward DeWitt
- Visual Guidance:
  - Blue route = Continue on I-96 West
  - Red X markers = Do not enter Exit 8

**Voice Assistance:**

> "Keep left! Do not take Exit 8. Continue on I-96 West."

**Design Objective:** Make the correct highway decision explicit at the point where directional clarity is most important.

<!-- Optional: Add Decision interface screenshot here -->
<!-- ![ClearTurn Decision Interface](images/decision.png) -->

---

### ✅ Stage 5 — CRUISE: Route Confirmation

**Scenario:** The highway maneuver has been completed correctly.

After the driver completes the intended maneuver, ClearTurn confirms the route and reduces the prominence of navigation information.

Exit warnings and detailed lane guidance disappear as the interface returns to a calmer navigation state.

**Interface Information:**
- Primary Action: **ROUTE CORRECT — CONTINUE ON I-96 W**
- Distance Remaining: 46 miles
- Estimated Arrival: 4:38 PM
- Next Important Maneuver: 31 miles

**Voice Assistance:**

> "Your route is correct. Continue on I-96 West toward Grand Rapids."

**Design Objective:** Confirm the completed maneuver and return the interface to normal highway navigation.

<!-- Optional: Add Route Confirmation screenshot here -->
<!-- ![ClearTurn Route Confirmation](images/confirmation.png) -->

---

## ✅ 3D Automotive Prototype

To demonstrate the navigation concept beyond static 2D interface designs, ClearTurn incorporates the HMI into a simplified 3D vehicle interior.

The prototype includes:

- A conceptual automotive dashboard
- A steering wheel
- A central navigation display
- Front-seat interior elements
- Integrated 2D navigation interface visuals
- Animated navigation-state transitions
- Coordinated voice guidance
- A rendered video demonstration

The 3D environment provides spatial context for evaluating how the navigation interface might appear within an automotive setting.

The model is a conceptual visualization and does not represent a production-ready vehicle interior.

### ▶️ [Watch the 3D Automotive Prototype](https://drive.google.com/file/d/143ysiMyBbOyITd-eDN69yIRz9erDiyrt/view?usp=drive_link)

---

## 🧠 Design Principle

> **Information should become more prominent as the driver's need to act increases, then recede after the decision has been completed.**

This principle guides the ClearTurn experience.

The design explores how an automotive navigation interface can balance trip awareness, timely guidance, and information simplicity.

---

## 📚 Lessons Learned, Limitations & Future Improvements

### Lessons Learned

Developing ClearTurn strengthened my understanding of how human-centered design principles can be translated from 2D interface concepts into a 3D automotive environment.

**1. Context-Aware Design**

I learned the importance of adapting information hierarchy to the driver's immediate needs, providing minimal guidance during normal highway travel and more prominent instructions at critical decision points.

**2. 2D-to-3D Integration**

Using Figma, Stitch AI, and Blender expanded my practical understanding of 3D visualization, spatial layout, camera positioning, and integrating digital interfaces into a vehicle interior.

**3. Multimodal Interaction**

Combining visual instructions with voice guidance highlighted the importance of coordinating different communication methods to create a consistent navigation experience.

### Project Limitations

ClearTurn is an exploratory design prototype rather than a fully functional automotive navigation system.

**1. Conceptual Simulation**

The navigation scenarios are predefined and do not respond dynamically to real-time vehicle location, traffic conditions, or driver behavior.

**2. Simplified Vehicle Interior**

The 3D environment focuses on demonstrating the navigation experience rather than representing a production-ready automotive interior.

**3. Limited Validation**

The proposed benefits of reducing unnecessary screen checking and improving highway decision clarity have not yet been evaluated through controlled usability testing or driving simulations.

### Future Improvements

**1. Interactive Navigation**

Develop a functional prototype capable of adapting visual and voice guidance to changing route conditions.

**2. Enhanced 3D Modeling**

Refine vehicle interior proportions, materials, lighting, and display placement to create a more realistic automotive experience.

**3. User Testing**

Conduct usability studies or simulated driving evaluations to assess glance behavior, instruction comprehension, cognitive workload, and driver confidence.

**4. Personalization**

Explore configurable voice-update intervals and accessibility preferences to accommodate different driver needs.

---

## 🎯 Key Takeaway

ClearTurn reinforced my understanding that effective automotive interface design is not simply about presenting more information, but about delivering the right information, at the right moment, in a form that supports clear and confident decisions.

This project represents my continued development in UX/UI design, automotive HMI concepts, 3D visualization, and digital prototyping.

---

## 📺 Project Demonstration

**[▶️ Watch ClearTurn — 3D Automotive Navigation HMI](https://drive.google.com/file/d/143ysiMyBbOyITd-eDN69yIRz9erDiyrt/view?usp=drive_link)**

---

## 👨‍💻 Project Author

**Lukman Adeyemi**  
UX/UI Design | 3D Visualization | Human-Centered Design

- **Email:** [Lukman.adeyemi05@gmail.com](mailto:Lukman.adeyemi05@gmail.com)
- **LinkedIn:** [linkedin.com/in/lukman-adeyemi0512](https://www.linkedin.com/in/lukman-adeyemi0512/)
- **GitHub:** [github.com/lukmanasquare](https://github.com/lukmanasquare)
- **Portfolio:** [lukman-asquarewebdesigns.com](https://lukman-asquarewebdesigns.com/)

---

*ClearTurn is an independent personal design concept created for portfolio demonstration and design exploration.*

