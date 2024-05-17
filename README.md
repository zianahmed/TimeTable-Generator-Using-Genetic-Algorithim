# Timetable Scheduling Problem using Genetic Algorithms

**Project Description:**

Timetable scheduling is a critical task in university environments, ensuring efficient allocation of resources while minimizing conflicts between classes, professors, and rooms. This project addresses this classical problem using genetic algorithms, where time slots are assigned to each section, professor, and room for teaching courses.

---

**Constraints:**

**Hard Constraints:**
- Classes must be scheduled in available classrooms.
- Classrooms must accommodate the section size.
- Professors cannot have overlapping lecture times.
- Sections cannot be assigned to different rooms simultaneously.
- Rooms cannot host different sections simultaneously.
- Each professor can teach a maximum of 3 courses.
- Each section can have a maximum of 5 courses per semester.
- Each course has two lectures per week, not on the same or adjacent days.
- Lab lectures must be conducted in two consecutive slots.

**Soft Constraints:**
- Theory classes are scheduled in the morning, lab sessions in the afternoon.
- Minimize the number of floors traversed by teachers/students.
- Maintain consistency of classrooms for classes throughout the week.
- Prefer longer blocks of continuous teaching time for teachers.

**Other Details:**
- Timetable covers 5 days a week, with morning sessions from 8:30 – 2:30 and afternoon sessions from 2:30 – 5:30.
- Chromosomes are binary encoded with course, type, section, professor, lecture details, and room information.
- Fitness function is based on the inverse sum of conflicts/clashes.

---

**Foundational Code:**

The provided code implements the classical genetic algorithms' cycle, including reproduction, crossover, and mutation. It uses tournament selection, crossover, and mutation operators to generate the next generation of solutions.

---

**Readme File:**

Please refer to the [project report](Project_Report) for detailed implementation, code, and results.

---


**Conclusion:**

This project aims to efficiently solve the timetable scheduling problem using genetic algorithms, ensuring optimal resource allocation while adhering to hard and soft constraints.
