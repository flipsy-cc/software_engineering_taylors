# Uni Guide – Requirements (draft, to be finalised by 6 Nov)

Priority uses MoSCoW. The 7 Must-haves are the scope of the prototype.

## Functional requirements

| ID | Area | Requirement | Priority |
| --- | --- | --- | --- |
| FR01 | Account | The system shall let students, lecturers and admins log in with their university credentials. | Must |
| FR02 | Navigation | The system shall show an interactive campus map with classrooms, lecture halls, libraries, cafés and offices. | Must |
| FR03 | Navigation | The system shall let users search for a place by name or room code and show a route to it, including accessible routes. | Must |
| FR04 | Navigation | The system shall show classroom and lecture hall details such as floor, capacity and equipment. | Should |
| FR05 | Schedule | The system shall show each student's class timetable in a daily and weekly view, with the room of each class. | Must |
| FR06 | Schedule | The system shall show exam dates and assignment deadlines and send reminders before them. | Must |
| FR07 | Announcements | The system shall send lecturers' announcements and class cancellation alerts to the students of that module. | Must |
| FR08 | Academic | The system shall show each student's attendance percentage per module. | Should |
| FR09 | Academic | The system shall show each student's grades, results and overall academic progress. | Should |
| FR10 | Campus life | The system shall list campus events and let users save them and get a reminder. | Should |
| FR11 | Campus life | The system shall provide Campus Talk, a discussion channel for students taking the same module. | Could |
| FR12 | Transport | The system shall show the campus bus schedule. | Should |
| FR13 | Transport | The system shall show the live location of campus buses on the map. | Could |
| FR14 | Food | The system shall show cafeteria menus and let users rate and comment on food outlets. | Should |
| FR15 | Services | The system shall let students book a study room or facility and show its live availability. | Should |
| FR16 | Services | The system shall let students search the library catalogue and reserve a book. | Could |
| FR17 | Services | The system shall show tuition fee amounts, due dates and payment information (view only). | Could |
| FR18 | Support | The system shall let users report lost or found items with a photo and location. | Could |
| FR19 | Support | The system shall let users report maintenance issues at a location. | Could |
| FR20 | Support | The system shall let students send a question to the student help desk and track its status. | Could |
| FR21 | Admin | The system shall let admins and lecturers publish announcements and events and update campus data. | Must |

## Non-functional requirements

| ID | Category | Requirement |
| --- | --- | --- |
| NFR01 | Performance | Search results and the map shall load within 3 seconds on campus Wi-Fi. |
| NFR02 | Performance | Announcements and cancellation alerts shall reach students within 1 minute of publishing. |
| NFR03 | Usability | A new student shall find a given classroom with the app within 5 minutes of first use, without help. |
| NFR04 | Accessibility | The app shall offer accessible routes, readable contrast and screen-reader labels. |
| NFR05 | Security | Only logged-in users shall access the app, with role-based access for students, lecturers and admins. |
| NFR06 | Privacy | Grades and attendance shall be visible only to the student and their lecturers; location data shall not be stored. |
| NFR07 | Reliability | The app shall be available 99% of the time during the semester. |
| NFR08 | Scalability | The system shall support at least 1,000 users at the same time. |
| NFR09 | Maintainability | Admins shall update campus data, menus and schedules without code changes. |
| NFR10 | Compatibility | The app shall run on current Android, iOS and desktop browsers. |
