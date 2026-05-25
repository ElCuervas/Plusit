# Plusit 
Streamlined labor management app for seasonal workers.

## Team
- **Sebastian Aillapan (Project Manager and Analyst)** 
- **John Fernandez (Designer and Analyst)**
    
## Figma Links
* [Plusit Interactive Design & Prototypes](https://www.figma.com/design/9IAGdbV9y2dXPuQIlkDHqM/Plusit?node-id=0-1&t=w2iEPmNojqyeBq7a-1)

## 1. About the Project
Plusit is a mobile application designed specifically for seasonal workers (formal temporary workers) in the agricultural, forestry, and packing sectors in the La Araucanía region, Chile.
The project was created to solve a critical User Experience (UX) gap: the disconnect between Human Resources departments and field workers who face conditions of low digital literacy, limited hardware (low-end phones), and intermittent or no connectivity.

## 2. Key Features (Value Proposition)
* **Offline Mode:** Ensures the app remains functional in rural areas with intermittent or no signal.
* **Fatt-Finger Friendly Design:** Large buttons and extended touch zones prevent errors for users with tired hands or damaged screens
* **Performance Simulator:** A visual tool to track daily yield per crate and estimate earnings in real-time.
* **Shift Swapping Dashboard:** A simplified system for workers to coordinate turn changes for personal or family needs
* **Visual Confirmation:** Clear status indicators like the "Permit Status Traffic Light" and "One-tap share with family" to simplify communication with loved ones and supervisors.

## 3. Strategy

The first step under the Elements of User Experience is the Strategy plane, which focuses on incorporating not only what the people running the application want to get out of it but what the users want to get out of the application.

From this approach, a Value Proposition Canvas is used to determine what the people want to earn from our solution and how we are going to respond to those needs.

![Value Proposition Canvas](Assets/Value%20Proposition%20Canvas.jpg)

## 4. Solutions Scope
The Solutions Scope defines the functional boundaries of Plusit. As defined in the "Five Planes" model of UX, this scope acts as the bridge between our Strategy (the "why") and the Structure/Skeleton (the "how"). The objective of this scope is to prevent "feature creep" (uncontrolled accumulation of features) and maintain a laser focus on the critical needs of our seasonal workers.

In-Scope (What we are building):

* **Attendance & Scheduling:** Offline-first attendance tracking and shift management.
* **Transparency:** Simplified salary visualization and daily yield (kilos/crates) counters.
* **Communication:** A simplified permit request system using voice notes and status "traffic light" indicators.
* **Extreme Accessibility:** Interfaces designed with "Fat-Finger Friendly" principles and cognitive load reduction.

Out-of-Scope (Constraints):

* **Complex Recruitment:** No CV uploading or job application modules, as our target user is already hired.
* **Heavy Media:** Video tutorials are excluded due to our users' mobile data constraints.
* **Full HR Accounting:** The app does not replace HR accounting software; it acts solely as a simplified UI to visualize data already processed by the company.

### UX Personas

![UX_Persona1](Assets/1.png)
![UX_Persona2](Assets/2.png)
![UX_Persona3](Assets/3.png)
## 5. Benchmark
In order to develop an application that meets the expectations and needs of users, it is essential to carry out an exhaustive analysis of existing applications on the market, especially those that are direct competitors. This process, known as benchmarking, allows us to identify both the shortcomings and the positive aspects of these applications, in order to integrate them optimally into our own product.

By studying competing applications, we can learn from their mistakes and avoid repeating them in our application. In addition, we can identify successful features and functionalities that we can adopt and implement in our solution, thus providing a superior experience to our users.
Products Evaluated: 

* **Direct Competitors:** Buk / Talana (Chilean HR apps focused on office environments).

* **Analog Competitor:** Agroptima (Field-based agricultural task management).

* **Design Reference:** BancoEstado (Chilean standard for accessibility and RUT-based login).

![Benchmark](Assets/BenchMarking.jpeg)


## 6. Navigation Flow

The navigation architecture of Plusit is designed with a **Dashboard-centric (Hub-and-Spoke)** pattern. This structure is specifically chosen to reduce cognitive load for seasonal workers with low digital literacy, as it provides a central, familiar starting point (the Home screen) for all primary tasks and prevents users from getting lost in deep, nested menus.
Key features of this navigation flow include:
* **Centralized Hub:** Every operational module (Salary Simulator, Shift Swap, Benefits, Performance, and Payments) is directly accessible from the main dashboard with a single tap.
* **Global Navigation Shortcut:** A global "+" button is integrated into the bottom navigation bar, providing instant, single-tap redirection to the Requests/Permits module from any screen.
* **Linear Task Flows:** Sub-processes, such as shift publishing or viewing detailed monthly payouts, follow a strict linear flow with clear back navigation to maintain context.
Below is the conceptual navigation flow of the Plusit application:

![Navigation Flow](Assets/Navegation%20Flow.jpg)

## 7. Customer Journey Map

The Customer Journey Map outlines the daily work cycle of **Héctor**, a 52-year-old seasonal harvester with over 20 years of experience in manual labor. Due to physical fatigue, calloused hands, and limited digital literacy, Héctor struggles with standard complex mobile interfaces. 
This map visualizes his journey across five key touchpoints in the Plusit application:
1. **Shift Swapping:** Coordinating schedule changes with peers to balance labor and family events.
2. **Harvesting & Yield Input:** Logging daily crates in real-time and calculating earnings using the simplified, oversized numeric keypad.
3. **Requesting Leave:** Submitting emergency permissions via voice note directly from the field, triggered easily using the navbar shortcut (+).
4. **Redeeming Benefits:** Accessing and claiming company incentives and performance-based rewards.
5. **Payout Day:** Reviewing monthly salary breakdowns, bonuses, and deductions in a simplified and transparent visual dashboard.
The journey demonstrates how Plusit's offline-first database, "fat-finger-friendly" touch zones, voice inputs, and visual status indicators directly mitigate the worker's field-based pain points.

![Customer Journey Map](Assets/Customer%20journey%20map.png)

## 8. Wireframes
This section presents the blueprint layout of the platform's core interfaces. The following wireframes illustrate the user journey from initial authentication to essential administrative actions, ensuring a clean, accessible, and user-centered operational flow.

**Wireframe - Login, Sign Up & Home Process:** Conceptualizes the user authentication lifecycle and onboarding path toward the main dashboard.

![Login](Assets/wireframe/Principios/Login.png)
![Login2](Assets/wireframe/Principios/Login%202.png)
![Register](Assets/wireframe/Principios/Register.png)
![Home](Assets/wireframe/Principios/Home.png)


**Wireframe - Time Off Request Process:** Outlines the simplified flow for submitting quick administrative permissions and short-term sick leaves.

![Permiso-dibujo](Assets/wireframe/Permisos/permisos_dibujo.png)
![Permiso-historial](Assets/wireframe/Permisos/Permisos%20(Historial).png)
![Permiso-proceso](Assets/wireframe/Permisos/Permisos%20(Solicitud).png)


**Wireframe - Vacation Request Process:** Displays the interactive calendar-driven steps to plan and request extended annual leave.

![Vacaciones-dibujo](Assets/wireframe/Vacaciones/Vacaciones_dibujo.png)
![Vacaciones-historial](Assets/wireframe/Vacaciones/Vacaciones%20(Historial).png)
![Vacaciones-proceso](Assets/wireframe/Vacaciones/Vacaciones%20(Solicitud).png)

**Wireframe - Salary Simulator Process:** Visualizes the dynamic calculation tool designed to estimate payroll metrics, bonuses, and net pay deductions.
![Simulador-dibujo](Assets/wireframe/Simulador%20de%20sueldo/Simulador_sueldo_dibujo.png)
![Simulador-historial](Assets/wireframe/Simulador%20de%20sueldo/Simulador.png)
![Simulador-proceso](Assets/wireframe/Simulador%20de%20sueldo/Simulador-Resultado.png)

