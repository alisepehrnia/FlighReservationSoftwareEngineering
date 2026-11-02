# ✈️ Flight Reservation – Software Engineering Modeling

A collection of **UML diagrams** and modeling exercises for a **flight reservation system**, created as part of a software engineering course.  
This repository focuses on the **design and analysis** phases—class, component, deployment, sequence, collaboration, and state diagrams—rather than on executable code.

---

## 📖 Overview

`FlighReservationSoftwareEngineering` documents the software architecture and behavior of a hypothetical airline booking system.  
The diagrams follow the **Unified Modeling Language (UML)** standard and can serve as:

- A reference for how a flight reservation system should be structured.
- A learning resource for UML notation and software design.
- A starting point for implementing the system in an object‑oriented language.

> **Note:** The repository contains **modeling artifacts only** (`.vsdx` source files and exported `.pdf` files). There is no runnable application in this repository.

---

## 🗂️ Repository Contents

### UML Diagrams

| Diagram | Source File | Exported PDF |
|---------|-------------|--------------|
| **Class Diagram** | `ClassDiagram.vsdx` | – |
| **Component Diagram** | `ComponentDiagram.vsdx` | `ComponentDiagram.pdf` |
| **Deployment Diagram** | `DeploymentDiagram.vsdx` | `DeploymentDiagram.pdf` |
| **Deployment Class Diagram** | `DeploymentClass.vsdx` | `DeploymentClass.pdf` |
| **Sequence Diagram** | `SequenceDiagram.vsdx` | `SequenceDiagram.pdf` |
| **Collaboration Diagram** | `CollaborationDiagram.vsdx` | `CollaborationDiagram.pdf` |
| **State Diagram** | `StateDiagram_AliSepehrnia.vsdx` | `StateDiagram_AliSepehrnia.pdf` |
| **Interaction Diagram** | `Interaction.vsdx` | – |

### Exercises

| Exercise | Source File | Exported PDF |
|----------|-------------|--------------|
| Exercise 1 | `Exercise1.vsdx` | – |
| Exercise 6 | `Exercise6.vsdx` | `Exercise6.pdf` |

### Final Version

The `Final/` directory contains a consolidated **Component Diagram** (`ComponentDiagram.vsdx`), representing the finalized architecture of the system.

---

## 🔍 Diagram Highlights

### Class Diagram
Defines the static structure of the flight reservation system: classes such as `Flight`, `Passenger`, `Booking`, `Payment`, `Aircraft`, `Airport`, and their attributes, methods, and relationships (associations, multiplicities, inheritance).

### Component Diagram
Shows the high‑level **components** of the system (e.g., Booking Service, Payment Service, Flight Management, User Interface) and their dependencies. The `Final/` folder contains the refined version.

### Deployment Diagram
Maps the **physical deployment** of the system: nodes (servers, client machines), artifacts, and communication paths.

### Sequence Diagram
Illustrates the **dynamic behavior** of a specific scenario—typically the flight booking process—showing the interaction between objects over time.

### Collaboration Diagram
An alternative view of the same interactions, emphasizing the **structural organization** of objects that collaborate to fulfill a use case.

### State Diagram
Models the **lifecycle of a key object** (e.g., a `Booking` or `Flight`), showing states and transitions triggered by events (e.g., *reserved → paid → cancelled*).

### Interaction Diagram
A general interaction model that complements the sequence and collaboration diagrams.

---

## 🛠️ Tools & Format

- **Source format:** Microsoft Visio (`.vsdx`).
- **Export format:** PDF (for easy viewing without Visio).
- **Compatible tools:**
  - Microsoft Visio (native).
  - [draw.io](https://app.diagrams.net/) / diagrams.net (can import and edit `.vsdx` files).
  - LibreOffice Draw (limited `.vsdx` support).

---

## 🚀 How to Use

1. **View the diagrams without Visio**  
   Open any `.pdf` file directly in GitHub or download it.

2. **Edit the diagrams**  
   Open the corresponding `.vsdx` file in Microsoft Visio, or import it into [draw.io](https://app.diagrams.net/) to modify and re‑export.

3. **Use as a design reference**  
   The diagrams can guide the implementation of a flight reservation system in Java, C#, Python, or any object‑oriented language.

---

## 📋 Typical System Scope (Based on the Models)

The diagrams model a system that likely supports:

- **Flight search and scheduling** (origin, destination, dates, availability).
- **Passenger management** (registration, profiles, documents).
- **Booking and reservation** (seat selection, itinerary, confirmation).
- **Payment processing** (methods, statuses, refunds).
- **Cancellation and modification** of bookings.
- **Administration** of flights, aircraft, and airports.

> Refer to the actual diagrams for the authoritative class names, attributes, and relationships.

---

## 🤝 Contributing

This is primarily a coursework artifact. If you spot modeling inconsistencies or want to extend the design (e.g., add use‑case diagrams or activity diagrams), feel free to open an issue or submit a pull request with the updated `.vsdx` file and an exported PDF.

---

## 📄 License

Feel free to use :)

---

## 🙏 Acknowledgements

- Diagrams created with **Microsoft Visio**.
- Modeling follows standard **UML** notation taught in software engineering courses.
