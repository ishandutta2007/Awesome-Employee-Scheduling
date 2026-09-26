# Awesome-Employee-Scheduling

# 📅 Top Employee Scheduling Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Employee Scheduling, Shift Scheduling, Workforce Rostering, Staff Scheduling, Time & Attendance, Shift Swapping & Workforce Management*
**Last updated: September 2026**

This repository tracks notable **SaaS/Hosted platforms** and **open-source GitHub projects** for **employee scheduling and workforce rostering**.

Employee scheduling software helps organizations create and publish employee schedules, manage availability, handle time-off requests, fill open shifts, enable shift swaps, optimize staffing levels, track labor costs, manage multiple locations, and integrate scheduling with time tracking, payroll and HR systems.

**Examples** include Deputy, When I Work, Homebase, Sling, Planday, Humanity, ZoomShift, Findmyshift, ScheduleAnywhere and Connecteam.

**Open-source emphasis:** This repository places particular emphasis on **self-hosted employee scheduling and rostering software**, while also including open-source optimization engines, constraint solvers, HR systems, time-and-attendance platforms, calendar components and other building blocks that can be combined into a complete Deputy/When I Work/Homebase-style platform.

A particularly important distinction is that an **open-source employee scheduling application** is different from an **open-source scheduling engine**. Projects such as Schichtplaner, Rota and Employee Shift Scheduler provide application-level scheduling functionality, while Timefold, OptaPlanner and OR-Tools primarily provide the optimization/constraint-solving layer needed to automatically construct schedules.

Contributions welcome! Open a PR to add or update entries. Please distinguish between complete scheduling applications, HR/ERP platforms, optimization engines, time-and-attendance systems and supporting infrastructure.

---

## Table of Contents

* [SaaS/Hosted Platforms](#saashosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)

  * [Complete Employee Scheduling & Rostering Applications](#complete-employee-scheduling--rostering-applications)
  * [HR/ERP Platforms with Scheduling Capabilities](#hrerpp-platforms-with-scheduling-capabilities)
  * [Scheduling & Constraint Optimization Engines](#scheduling--constraint-optimization-engines)
  * [Time & Attendance Building Blocks](#time--attendance-building-blocks)
  * [Calendar & Scheduling UI Components](#calendar--scheduling-ui-components)
  * [Additional Strong Open-Source Options](#additional-strong-open-source-options)
* [Commercial → Open-Source Capability Mapping](#commercial--open-source-capability-mapping)
* [Framework for Building a Self-Hosted Employee Scheduling Platform](#framework-for-building-a-self-hosted-employee-scheduling-platform)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

---

## SaaS/Hosted Platforms

* **[Deputy](https://www.deputy.com/)**
  Employee scheduling and workforce management platform covering scheduling, timekeeping, compliance, HR, payroll and workforce communication, with automated/AI-assisted scheduling capabilities.

* **[When I Work](https://wheniwork.com/)**
  Employee scheduling and workforce management platform focused on shift scheduling, employee availability, time tracking, team communication and shift changes.

* **[Homebase](https://www.joinhomebase.com/)**
  SMB-focused employee scheduling platform combining schedule building, availability, time-off management, shift swaps, time tracking, labor-cost management and payroll-related workflows.

* **[Sling](https://getsling.com/)**
  Employee scheduling and workforce management software providing shift scheduling, availability, time-off management, shift trading, messaging and labor-cost tools.

* **[Planday](https://www.planday.com/)**
  Employee scheduling and workforce management platform with schedules, schedule templates, open shifts, employee availability, time tracking, payroll workflows and scheduling rules.

* **[Humanity Schedule](https://tcpsoftware.com/products/humanity/)**
  Workforce scheduling platform from TCP Software supporting automated scheduling, demand forecasting, employee availability, shift management, compliance rules, open shifts and self-service scheduling.

* **[ZoomShift](https://www.zoomshift.com/)**
  Employee scheduling software designed for hourly workforces, with schedule templates, availability, time-off requests, open shifts, shift swaps, notifications and time-clock functionality.

* **[Findmyshift](https://www.findmyshift.com/)**
  Online employee scheduling platform using a spreadsheet-style schedule editor with drag-and-drop scheduling, shift requests, labor-cost tracking, time and attendance and employee communication.

* **[ScheduleAnywhere](https://www.scheduleanywhere.com/)**
  Workforce scheduling platform focused on recurring shift schedules, employee availability, multi-department scheduling and self-scheduling.

* **[Connecteam](https://connecteam.com/)**
  Deskless-workforce management platform combining employee scheduling with time tracking, communication, task management, training and operational workflows.

* **[7shifts](https://www.7shifts.com/)**
  Restaurant-focused employee scheduling and workforce management platform covering scheduling, labor compliance, time tracking, team communication and labor-cost management.

* **[Quinyx](https://www.quinyx.com/)**
  Enterprise workforce management platform covering employee scheduling, demand forecasting, time and attendance, workforce optimization and labor planning.

* **[Workforce.com](https://www.workforce.com/)**
  Workforce management platform covering employee scheduling, time tracking, payroll, labor compliance, employee communication and workforce analytics.

* **[Skello](https://www.skello.io/)**
  Workforce management platform focused on employee schedules, time tracking, leave, payroll preparation and labor-rule compliance.

* **[Shyft](https://www.myshyft.com/)**
  Employee scheduling and workforce communication platform focused on shift management, shift swapping, open shifts and employee communication.

* **[RotaCloud](https://rotacloud.com/)**
  Online staff scheduling and rota-management software covering employee schedules, leave, availability, shift changes, time tracking and workforce communication.

* **[Rotaready](https://rotaready.co.uk/)**
  Workforce management platform for hospitality and other shift-based organizations covering scheduling, time and attendance, payroll and workforce planning.

* **[Smartplan](https://smartplanapp.io/)**
  Employee scheduling and shift-planning platform focused on staff rosters, availability, time-off, shift changes and workforce communication.

* **[Papershift](https://www.papershift.com/)**
  Cloud workforce management platform covering employee scheduling, time tracking, absence management and workforce administration.

* **[Factorial](https://factorialhr.com/)**
  HR platform with employee scheduling, time tracking, shift management, absence management and workforce administration capabilities.

* **[BambooHR](https://www.bamboohr.com/)**
  HR platform that provides employee-management and workforce administration capabilities that can complement dedicated scheduling systems.

* **[TimeClock Plus](https://tcpsoftware.com/products/timeclock-plus/)**
  Workforce management and time-and-attendance platform from TCP Software that complements scheduling and workforce planning.

---

## Open-Source GitHub Projects

> **Open-source emphasis:** The projects below are intentionally broader than a simple list of scheduling libraries. Complete self-hosted scheduling applications are listed first, followed by HR/ERP systems, optimization engines and reusable components that can help build a full employee scheduling platform.

### Complete Employee Scheduling & Rostering Applications

* **[Schichtplaner](https://github.com/lennystepn-hue/schichtplaner)**
  Self-hosted open-source shift-planning and workforce-management application with shift planning, employee management, availability/preferences, real-time collaboration, time tracking and schedule optimization.

* **[Rota](https://github.com/jonathanhu237/rota)**
  Open-source employee rostering application covering scheduling, availability, shift coverage, leave and attendance workflows with separate employee and administrator experiences.

* **[Timeshift](https://github.com/ConaryLabs/Timeshift)**
  Self-hostable scheduling platform designed for organizations with complex shift rules, including seniority-based overtime queues, vacation bidding, leave rules and 24/7 coverage requirements.

* **[Employee Shift Scheduler](https://github.com/SirChri/employee-shift-scheduler)**
  Open-source employee scheduling web application built with React, Spring Boot and PostgreSQL, with employee management, scheduling and recurring event functionality.

* **[Shift Scheduler](https://github.com/robol/shift-scheduler)**
  Open-source employee shift scheduler that calculates timetables according to employee preferences and organizational constraints using integer optimization.

* **[Shift Scheduler](https://github.com/oasido/shift-scheduler)**
  Open-source web application for employee shift scheduling and employee absence-request management, with employee and manager workflows and Docker deployment.

* **[Employee Scheduling](https://github.com/martinmicunda/employee-scheduling)**
  Open-source employee scheduling and management application designed to make employee scheduling easier, faster and mobile-friendly.

* **[ShiftWizard](https://github.com/NaphtaliO/ShiftWizard)**
  Free and open-source employee rostering system with separate employer and employee interfaces and self-hosted deployment.

* **[Employee Scheduling System](https://github.com/mperry-dev/employee_scheduling_system)**
  Open-source employee scheduling tool using OptaPlanner for automatic allocation of employees to shifts based on availability and scheduling constraints.

* **[Scheduler](https://github.com/averude/Scheduler)**
  Open-source employee rostering and work-scheduling web service with employee, department and shift administration and automated schedule generation.

### HR/ERP Platforms with Scheduling Capabilities

* **[ERPNext](https://github.com/frappe/erpnext)**
  Open-source ERP platform with employee management, HR, attendance, leave, payroll and related workforce functionality that can be extended into a complete scheduling system.

* **[Frappe HR](https://github.com/frappe/hrms)**
  Open-source HR and workforce-management application for the Frappe framework with employee records, attendance, leave, payroll and HR workflows.

* **[Odoo Community](https://github.com/odoo/odoo)**
  Open-source business-management platform whose HR ecosystem can be extended with employee management, attendance, time off, planning and workforce scheduling functionality.

* **[OrangeHRM](https://github.com/orangehrm/orangehrm)**
  Open-source HR management platform covering employee administration, leave, attendance and workforce-management functionality that can serve as the employee-data foundation for a scheduling system.

* **[TimeTrex Community Edition](https://github.com/timetrex/timetrex)**
  Open-source workforce management platform covering employee management, time and attendance, scheduling, payroll and related workforce processes.

### Scheduling & Constraint Optimization Engines

* **[Timefold](https://github.com/TimefoldAI/timefold-solver)**
  Open-source constraint-solving and optimization engine for planning problems including employee rostering and shift scheduling. Timefold's employee-scheduling examples support availability, skills, fairness and other scheduling constraints.

* **[Timefold Quickstarts](https://github.com/TimefoldAI/timefold-quickstarts)**
  Collection of practical optimization examples including employee shift scheduling, employee rostering, task assignment and other planning problems.

* **[Google OR-Tools](https://github.com/google/or-tools)**
  Open-source optimization suite supporting constraint programming, linear programming, mixed-integer programming and routing; particularly useful for building automated employee scheduling and rostering engines.

* **[OptaPlanner](https://github.com/kiegroup/optaplanner)**
  Open-source constraint-solving technology for planning and scheduling problems, including employee rostering and resource allocation.

* **[OptaPlanner Quickstarts](https://github.com/kiegroup/optaplanner-quickstarts)**
  Practical examples for constraint-solving applications, including employee scheduling where shifts are assigned according to employee availability and required skills.

* **[Pyomo](https://github.com/Pyomo/pyomo)**
  Open-source Python-based mathematical optimization modeling framework suitable for formulating workforce scheduling, rostering and labor-cost optimization problems.

* **[PuLP](https://github.com/coin-or/pulp)**
  Open-source Python linear-programming modeler useful for constructing employee assignment, shift coverage and workforce optimization models.

* **[SCIP](https://github.com/scipopt/scip)**
  Open-source optimization suite for mixed-integer programming and constraint programming that can be used to solve complex workforce scheduling problems.

### Time & Attendance Building Blocks

* **[Kimai](https://github.com/kimai/kimai)**
  Open-source time-tracking platform that can provide the time and labor-tracking layer around an employee scheduling system.

* **[TimeTrex](https://github.com/timetrex/timetrex)**
  Open-source workforce management platform combining time and attendance, employee management, scheduling and payroll-related functionality.

* **[ERPNext HRMS](https://github.com/frappe/hrms)**
  Provides employee records, attendance, leave and payroll functionality that can be connected to a custom shift-scheduling engine.

* **[Odoo](https://github.com/odoo/odoo)**
  Provides employee, attendance, time-off and planning functionality that can serve as the workforce-management layer surrounding a custom scheduling engine.

### Calendar & Scheduling UI Components

* **[FullCalendar](https://github.com/fullcalendar/fullcalendar)**
  Open-source JavaScript calendar library with powerful event visualization and scheduling interfaces, useful for building drag-and-drop employee roster interfaces.

* **[React Big Calendar](https://github.com/jquense/react-big-calendar)**
  React calendar component suitable for constructing custom employee scheduling, shift-management and resource-calendar interfaces.

* **[Cal.com](https://github.com/calcom/cal.com)**
  Open-source scheduling infrastructure and calendar platform that can provide reusable scheduling, availability and booking concepts for workforce applications.

* **[rrule](https://github.com/jakubroztocil/rrule)**
  Open-source recurrence-rule library useful for implementing recurring shifts, repeating schedules and complex calendar patterns.

### Additional Strong Open-Source Options

* **[Nextcloud Calendar](https://github.com/nextcloud/calendar)**
  Open-source calendar application useful as a calendar and availability layer around a custom employee scheduling platform.

* **[Nextcloud](https://github.com/nextcloud/server)**
  Self-hosted collaboration platform that can provide identity, files, calendars, notifications and collaboration infrastructure around an employee scheduling application.

* **[Mattermost](https://github.com/mattermost/mattermost)**
  Open-source team collaboration platform suitable for employee scheduling notifications, team communication and shift-related discussions.

* **[Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)**
  Open-source communication platform that can provide messaging and workforce communication around a self-hosted scheduling system.

* **[ntfy](https://github.com/binwiederhier/ntfy)**
  Open-source notification service useful for sending schedule publication, shift-change and open-shift alerts.

* **[Gotify](https://github.com/gotify/server)**
  Self-hosted push-notification server suitable for employee schedule and shift notifications.

* **[n8n](https://github.com/n8n-io/n8n)**
  Open-source workflow automation platform useful for connecting scheduling with HR, payroll, email, messaging, attendance and notification systems.

* **[Node-RED](https://github.com/node-red/node-red)**
  Open-source flow-based automation platform useful for integrating employee scheduling with operational systems and notifications.

* **[PostgreSQL](https://github.com/postgres/postgres)**
  Open-source relational database suitable for storing employees, shifts, availability, leave, qualifications, locations and scheduling constraints.

* **[Redis](https://github.com/redis/redis)**
  In-memory data store useful for caching schedules, distributed locks, queues and real-time workforce scheduling workflows.

* **[Grafana](https://github.com/grafana/grafana)**
  Open-source observability and analytics platform useful for workforce dashboards, staffing metrics, overtime monitoring and schedule-performance reporting.

* **[Metabase](https://github.com/metabase/metabase)**
  Open-source business intelligence platform suitable for employee scheduling analytics, labor-cost reporting and workforce dashboards.

* **[Apache Superset](https://github.com/apache/superset)**
  Open-source data visualization and BI platform useful for analyzing staffing levels, labor costs, attendance and scheduling efficiency.

* **[DuckDB](https://github.com/duckdb/duckdb)**
  Open-source analytical database useful for local and embedded workforce analytics.

* **[Polars](https://github.com/pola-rs/polars)**
  High-performance open-source DataFrame library suitable for workforce scheduling analytics and large employee/shift datasets.

* **[Pandas](https://github.com/pandas-dev/pandas)**
  Open-source Python data-analysis library useful for workforce reporting, schedule analysis and preprocessing optimization inputs.

---

## Commercial → Open-Source Capability Mapping

| Commercial Platform  | Primary Scheduling Focus                              | Open-Source Equivalents / Building Blocks                        |
| -------------------- | ----------------------------------------------------- | ---------------------------------------------------------------- |
| **Deputy**           | Scheduling + time + attendance + workforce management | Frappe HR / ERPNext + Timefold / OR-Tools + FullCalendar + Kimai |
| **When I Work**      | Scheduling + availability + team communication        | Schichtplaner + FullCalendar + Mattermost + ntfy                 |
| **Homebase**         | SMB scheduling + time clock + communication           | ERPNext + Frappe HR + TimeTrex + FullCalendar                    |
| **Sling**            | Scheduling + messaging + shift management             | Schichtplaner + Mattermost + FullCalendar + n8n                  |
| **Planday**          | Rota planning + availability + time tracking          | ERPNext / Frappe HR + Timefold + FullCalendar                    |
| **Humanity**         | Enterprise scheduling + optimization + compliance     | Timefold / OR-Tools + Frappe HR / ERPNext + FullCalendar         |
| **ZoomShift**        | Simple scheduling + availability + shift swaps        | Schichtplaner + Shift Scheduler + FullCalendar                   |
| **Findmyshift**      | Spreadsheet-style scheduling + labor tracking         | Shift Scheduler + FullCalendar + Kimai                           |
| **ScheduleAnywhere** | Recurring schedules + multi-department rostering      | ERPNext / Frappe HR + Timefold + FullCalendar                    |
| **Connecteam**       | Deskless workforce + scheduling + communication       | Frappe HR + Schichtplaner + Mattermost + n8n                     |
| **7shifts**          | Restaurant scheduling + labor management              | Timefold / OR-Tools + ERPNext / Odoo + FullCalendar              |
| **Quinyx**           | Enterprise WFM + forecasting + optimization           | Timefold / OR-Tools + ERPNext + Grafana                          |
| **Workforce.com**    | Workforce management + labor optimization             | ERPNext + Timefold + OR-Tools + Grafana                          |
| **Skello**           | Scheduling + time + leave + payroll workflows         | Frappe HR + Timefold + FullCalendar                              |
| **Shyft**            | Shift swapping + employee communication               | Schichtplaner + Mattermost / Rocket.Chat + ntfy                  |
| **RotaCloud**        | Rota scheduling + leave + time tracking               | Schichtplaner + Frappe HR + FullCalendar                         |
| **Rotaready**        | Hospitality workforce management                      | ERPNext + Timefold + Kimai + Grafana                             |

> **Important:** These mappings are **capability-oriented rather than feature-for-feature replacements**. Commercial products combine scheduling, mobile applications, notifications, payroll integrations, compliance rules, forecasting, analytics, customer support and hosted infrastructure. An equivalent self-hosted system will generally require several open-source components.

---

## Framework for Building a Self-Hosted Employee Scheduling Platform

A practical open-source architecture for building a **Deputy / When I Work / Homebase / Planday-style employee scheduling platform** can be assembled from the following components:

| Layer                     | Open-Source Technologies                        |
| ------------------------- | ----------------------------------------------- |
| Employee / HR             | Frappe HR · ERPNext · Odoo · OrangeHRM          |
| Scheduling Application    | Schichtplaner · Rota · Employee Shift Scheduler |
| Scheduling UI             | FullCalendar · React Big Calendar               |
| Automatic Scheduling      | Timefold · OR-Tools · OptaPlanner               |
| Mathematical Optimization | Pyomo · PuLP · SCIP                             |
| Employee Availability     | Frappe HR · ERPNext · Custom PostgreSQL models  |
| Shift Swapping            | Custom workflow + FullCalendar                  |
| Open Shifts               | Custom scheduling workflow + notifications      |
| Skills Matching           | Timefold · OR-Tools                             |
| Labor Constraints         | Timefold · OR-Tools · OptaPlanner               |
| Time & Attendance         | TimeTrex · Kimai · ERPNext                      |
| Leave Management          | Frappe HR · ERPNext · Odoo                      |
| Payroll                   | ERPNext · Odoo                                  |
| Notifications             | ntfy · Gotify                                   |
| Team Communication        | Mattermost · Rocket.Chat                        |
| Calendar                  | FullCalendar · Nextcloud Calendar               |
| Workflow Automation       | n8n · Node-RED                                  |
| Database                  | PostgreSQL                                      |
| Cache / Queues            | Redis                                           |
| Analytics                 | DuckDB · Polars · Pandas                        |
| BI                        | Grafana · Metabase · Apache Superset            |
| API                       | FastAPI · Django · Spring Boot                  |
| Authentication            | Keycloak                                        |
| Deployment                | Docker · Kubernetes                             |

### Recommended Architecture

```text
                    ┌───────────────────────────────┐
                    │       Employee Web / App      │
                    │ Schedule · Availability       │
                    │ Leave · Swaps · Open Shifts   │
                    └───────────────┬───────────────┘
                                    │
                                    ▼
                    ┌───────────────────────────────┐
                    │       Scheduling API          │
                    │ Employees · Shifts · Rules    │
                    │ Locations · Skills · Leave    │
                    └───────────────┬───────────────┘
                                    │
                   ┌────────────────┴────────────────┐
                   │                                 │
                   ▼                                 ▼
        ┌────────────────────┐             ┌────────────────────┐
        │ Scheduling Engine  │             │ Employee / HR Data │
        │ Timefold / OR-Tools│             │ Frappe HR / ERPNext│
        │ OptaPlanner        │             │ Odoo / OrangeHRM   │
        └──────────┬─────────┘             └──────────┬─────────┘
                   │                                  │
                   └────────────────┬─────────────────┘
                                    ▼
                    ┌───────────────────────────────┐
                    │          PostgreSQL           │
                    │ Employees · Shifts · Rules    │
                    │ Availability · Attendance     │
                    └───────────────┬───────────────┘
                                    │
              ┌─────────────────────┼─────────────────────┐
              ▼                     ▼                     ▼
       ┌────────────┐        ┌────────────┐       ┌────────────┐
       │ Attendance │        │ Notifications│      │ Analytics  │
       │ TimeTrex   │        │ ntfy/Gotify │       │ Grafana    │
       │ Kimai      │        │ Mattermost  │       │ Metabase   │
       └────────────┘        └────────────┘       └────────────┘
```

### Core Scheduling Workflow

```text
Employee Data
      ↓
Availability & Time-Off
      ↓
Required Staffing Levels
      ↓
Skills / Qualifications
      ↓
Labor Rules & Constraints
      ↓
Demand Forecast
      ↓
Constraint Optimization
      ↓
Draft Schedule
      ↓
Manager Review
      ↓
Publish Schedule
      ↓
Employee Notifications
      ↓
Shift Swaps / Open Shifts
      ↓
Time & Attendance
      ↓
Payroll
      ↓
Workforce Analytics
```

The core scheduling problem can be modeled as:

```text
Employees
    +
Shifts
    +
Availability
    +
Skills
    +
Coverage Requirements
    +
Labor Rules
    +
Employee Preferences
    +
Fairness Constraints
    +
Labor Cost
        ↓
Constraint Solver
        ↓
Optimized Employee Roster
```

The most important open-source distinction is that **Timefold / OR-Tools / OptaPlanner solve the optimization problem**, while systems such as **Schichtplaner, Rota, ERPNext/Frappe HR and TimeTrex provide much more of the surrounding application functionality**.

---

## Open-Source Capability Matrix

| Capability                | Commercial Platforms | Strong Open-Source Options             |
| ------------------------- | -------------------- | -------------------------------------- |
| Employee Management       | ✓                    | Frappe HR · ERPNext · Odoo · OrangeHRM |
| Shift Creation            | ✓                    | Schichtplaner · Rota · FullCalendar    |
| Drag-and-Drop Scheduling  | ✓                    | FullCalendar · React Big Calendar      |
| Schedule Templates        | ✓                    | Custom + FullCalendar · ERPNext        |
| Employee Availability     | ✓                    | Frappe HR · ERPNext · Custom           |
| Automatic Scheduling      | ✓                    | Timefold · OR-Tools · OptaPlanner      |
| Constraint Scheduling     | ✓                    | Timefold · OR-Tools · Pyomo · SCIP     |
| Skills Matching           | ✓                    | Timefold · OR-Tools                    |
| Shift Swapping            | ✓                    | Custom workflow + scheduler            |
| Open Shifts               | ✓                    | Custom + notifications                 |
| Employee Preferences      | ✓                    | Timefold · custom application          |
| Fairness Optimization     | ✓                    | Timefold · OR-Tools                    |
| Coverage Optimization     | ✓                    | Timefold · OR-Tools                    |
| Labor Cost Optimization   | ✓                    | OR-Tools · Timefold · Pyomo            |
| Recurring Shifts          | ✓                    | FullCalendar · rrule · Schichtplaner   |
| Multi-Location Scheduling | ✓                    | ERPNext · Odoo + custom                |
| Leave Management          | ✓                    | Frappe HR · ERPNext · Odoo             |
| Time & Attendance         | ✓                    | TimeTrex · Kimai · ERPNext             |
| Payroll                   | ✓                    | ERPNext · Odoo                         |
| Team Messaging            | ✓                    | Mattermost · Rocket.Chat               |
| Push Notifications        | ✓                    | ntfy · Gotify                          |
| Calendar Integration      | ✓                    | Nextcloud Calendar · Cal.com           |
| Workflow Automation       | ✓                    | n8n · Node-RED                         |
| Workforce Analytics       | ✓                    | Grafana · Metabase · Superset          |
| Database                  | ✓                    | PostgreSQL                             |
| API                       | ✓                    | FastAPI · Django · Spring Boot         |
| Authentication            | ✓                    | Keycloak                               |

---

## How to Contribute

1. Fork the repository.

2. Add or edit entries in `README.md` following the existing format.

3. Include the official website or GitHub repository.

4. Clearly identify whether the project is **SaaS/Hosted**, **Open Source**, **Scheduling Application**, **HR/ERP**, **Optimization Engine**, **Time & Attendance**, or a **Supporting Building Block**.

5. Prefer actively maintained open-source repositories.

6. Include the project's license when known.

7. Distinguish complete employee scheduling applications from scheduling libraries and optimization engines.

8. Add new self-hosted employee scheduling and rostering applications.

9. Add new employee scheduling algorithms and constraint solvers.

10. Add projects supporting availability, shift swaps, open shifts and employee preferences.

11. Add integrations with HR, payroll, attendance and workforce-management systems.

12. Submit a pull request with a short explanation of the addition or update.

⭐ **Star the repository if you find it useful!**

---

## Disclaimer

* This repository is a **curated directory**, not a ranking or endorsement of any particular product.
* Commercial products and features change frequently; verify current capabilities, pricing, licensing and integrations with the vendor.
* Open-source projects vary substantially in maturity, maintenance activity, documentation, scalability and production readiness.
* An optimization engine such as **Timefold, OR-Tools or OptaPlanner** is not by itself a complete employee scheduling application.
* A complete self-hosted alternative to a commercial workforce-management platform may require several independent open-source components.
* Scheduling implementations should be reviewed for applicable labor laws, collective agreements, overtime rules, rest periods, data protection and organizational policies.
* Always review the license of each open-source project before using it commercially.
* Project links and availability may change over time.

---

**Made for developers, HR teams, operations teams & builders exploring the open-source workforce-management ecosystem.**
**Let's make employee scheduling more programmable, transparent and self-hostable.**
