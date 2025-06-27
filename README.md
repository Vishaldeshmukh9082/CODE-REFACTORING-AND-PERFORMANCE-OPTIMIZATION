# CODE-REFACTORING-AND-PERFORMANCE-OPTIMIZATION 
 
*COMPANY NAME*: CODDETECH IT SOLUTIONS

*NAME*: Vishal Sanjay Deshmukh

*INTERN ID*: CT6MTDK659

*DOMAIN*: SOFTWARE DEVELOPMENT

*DURATION*: 6 MONTHS

*MENTOR*: NEELA SANTOSH

---

## 🔍 Introduction  
The original project was a console-based Java application for collaborative farming. It handled user registrations, land listings, and basic farmer-company interaction via command-line I/O and internal data structures.

To improve usability, readability, and performance, I **refactored** the entire architecture into a modern **Android application** using **Java, XML layouts, and MySQL** as the backend database.

---

## 🔄 Refactoring Overview

| Original Component       | Refactored To                      | Impact on Readability              |
|--------------------------|------------------------------------|------------------------------------|
| Console-based UI         | Android XML Layouts                | Clear separation of UI and logic   |
| Java classes with `Scanner` | Android Activities and Fragments   | Modular, lifecycle-aware design    |
| In-memory user data      | Persistent storage via MySQL       | Real-time data access, permanent storage |
| Monolithic code logic    | Separated into adapters, models, and services | Easier to maintain and extend     |
| Manual navigation        | Android navigation components      | Smooth UI flow                     |

---

## ⚙️ Performance Optimizations

| Feature/Module           | Before (Console App)               | After (Android App)                | Performance Impact                 |
|--------------------------|------------------------------------|------------------------------------|------------------------------------|
| User input/output        | Blocking, linear flow              | Event-driven UI                    | Responsive UX                      |
| Data access              | Static HashMaps                    | Structured MySQL queries           | Persistent, scalable data access   |
| Repeated DB calls        | None                               | Optimized with query filtering     | Reduced load time                  |
| View rendering           | Not applicable                     | RecyclerView for dynamic lists     | Smooth scrolling and efficient UI |
| App architecture         | No separation of concerns          | MVC/MVVM-style modular structure   | Easier debugging and extension     |

---

## OUTPUT

![Image](https://github.com/user-attachments/assets/dd15edb7-26b9-40e0-90dc-85b24887e271)
![Image](https://github.com/user-attachments/assets/96ce3969-b457-492f-b102-076a50d59563)
![Image](https://github.com/user-attachments/assets/50e0234d-526d-4d63-bb37-4eaa07e65c5b)
![Image](https://github.com/user-attachments/assets/e17fc5c4-fadc-42e9-a189-07a2e8730b54)
![Image](https://github.com/user-attachments/assets/160bc4aa-5b8b-4b92-b4f3-19ef8274579d)
![Image](https://github.com/user-attachments/assets/fa62dc05-b3cd-41c0-a410-c93102949140)
