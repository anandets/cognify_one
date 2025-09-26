# Requirements

## Functional Requirements

**FR1:** The system shall provide a unified dashboard for Institute Owners showing student enrollment, revenue, attendance rates, and key performance metrics in a single view.

**FR2:** The system shall enable Teachers to create and upload course content including videos, PDFs, text materials, and quizzes through a drag-and-drop interface.

**FR3:** The system shall automatically track student attendance for both online and offline classes with manual override capabilities for Teachers.

**FR4:** The system shall send automated WhatsApp notifications to Parents for attendance, assignments, fee reminders, and progress updates.

**FR5:** The system shall provide a mobile-responsive Progressive Web App (PWA) that works offline and syncs when internet is available.

**FR6:** The system shall support course content consumption on mobile devices with download capabilities for offline access.

**FR7:** The system shall integrate with Razorpay payment gateway for fee collection with support for installments and EMI options.

**FR8:** The system shall provide role-based access control with distinct permissions for Owner, Academic Head, Teacher, Admin Staff, Student, and Parent roles.

**FR9:** The system shall automatically generate progress reports for students showing completion rates, assessment scores, and attendance patterns.

**FR10:** The system shall enable bulk SMS and email communication with customizable templates for different stakeholder groups.

**FR11:** The system shall provide basic analytics dashboard showing student performance trends, popular courses, and revenue metrics.

**FR12:** The system shall support Hindi and English language interfaces with easy switching between languages.

**FR13:** The system shall enable Students to submit assignments through mobile devices with photo upload capabilities.

**FR14:** The system shall automatically calculate and display fee outstanding, payments received, and send reminder notifications.

**FR15:** The system shall provide a student portal showing course progress, upcoming assignments, examination schedules, and announcements.

## Non-Functional Requirements

**NFR1:** The system shall load core functionality within 3 seconds on 3G networks and 1 second on 4G/WiFi connections.

**NFR2:** The system shall maintain 99.5% uptime during business hours (9 AM to 9 PM IST) with automated backup and recovery.

**NFR3:** The system shall support up to 1000 concurrent users per institute without performance degradation.

**NFR4:** The system shall consume less than 10MB of data per student per month for typical usage patterns.

**NFR5:** The system shall work offline for core learning activities (content consumption, assignment submission) and sync when connectivity is restored.

**NFR6:** The system shall encrypt all sensitive data (student records, payment information) using AES-256 encryption.

**NFR7:** The system shall comply with Indian data protection requirements and store all data within Indian borders.

**NFR8:** The system shall provide simple, intuitive interfaces requiring no more than 2 clicks to reach common functions.

**NFR9:** The system shall automatically backup all data daily and maintain 30-day backup history.

**NFR10:** The system shall scale to support 10,000 students per institute without architectural changes.

**NFR11:** The system shall integrate with existing tools through REST APIs without requiring custom development.

**NFR12:** The system shall support multiple Indian languages with complete UI translation (not just content).

---
