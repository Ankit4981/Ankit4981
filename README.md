📘 Smart Campus Assistant – Dialogflow ES Chatbot
IBCP – CRS Artificial Intelligence Project

Student Name: Ankit Pradhan
CRN: 100389
School: Viraj International School
Course: IBCP – CRS Artificial Intelligence

🧭 Project Overview

The Smart Campus Assistant is an AI-powered chatbot built using Dialogflow ES to help students, teachers, parents, and visitors navigate the school campus easily.

It provides quick answers about:

Department locations

Office locations

Events & venues

Campus timings

Transport options

Rules & policies

Cafeteria menu

Sports facilities

Admission details

Lost & found

The chatbot works 24/7 and improves communication on campus.

🎯 Objectives

Understand user needs through research

Build natural conversations using intents & entities

Implement slot-filling & follow-up contexts

Test and troubleshoot the chatbot

Deploy and document the project

Demonstrate AI skills for the IBCP CRS course

🗂️ Repository Structure

Smart-Campus-Assistant/
│
├── README.md                # Main documentation
│
├── dialogflow/              # Intents & Entities folder
│   ├── intents/
│   ├── entities/
│
├── documents/
│   └── Smart_Campus_Assistant_Project_Report.pdf
│
└── screenshots/
    ├── intents_list.png
    ├── entities_list.png
    ├── flowchart.png
    └── testing_results.png

🤖 Intents (15 Total)

| Intent Name              | Purpose                               |
| ------------------------ | ------------------------------------- |
| Welcome Intent           | Greets users                          |
| DepartmentLocationIntent | Shows department locations            |
| EventInfoIntent          | Gives event venue details             |
| CampusTimingIntent       | Shows timings of campus facilities    |
| StaffOfficeIntent        | Shows staff office locations          |
| RulesIntent              | Explains campus rules & policies      |
| TransportIntent          | Gives transport & parking info        |
| EmergencyContactIntent   | Shows emergency contact numbers       |
| CafeteriaMenuIntent      | Displays cafeteria menu               |
| LibraryHoursIntent       | Shows library hours & rules           |
| AdmissionQueryIntent     | Explains admission process            |
| FeesIntent               | Provides fee-related information      |
| SportsFacilityIntent     | Shows sports ground & court locations |
| LostAndFoundIntent       | Helps with lost item reports          |
| FallbackIntent           | Handles unrecognized queries          |

🔤 Entities (10 Total)

| Entity Name     | Samples                           |
| --------------- | --------------------------------- |
| day_name        | monday, tuesday, friday           |
| department_name | computer science, maths, english  |
| event_name      | seminar, workshop, competition    |
| faculty_role    | principal, teacher, coach         |
| hostel_type     | boys hostel, girls hostel         |
| location_name   | admin block, science block        |
| meal_type       | lunch, snacks, breakfast          |
| office_name     | accounts office, principal office |
| rule_type       | dress code, mobile usage          |
| transport_type  | bus, cycle, walk, car             |

🔄 Flowchart

                      [ Welcome Intent ]
                             |
     -----------------------------------------------------
     |                        |                         |
[ Department ]        [ Event Query ]          [ Timing Query ]
     |                        |                         |
DepartmentLocation      EventInfoIntent         CampusTimingIntent


                 (Offers follow-up responses)
                             |
                      [ Additional Queries ]
                             |
     -----------------------------------------------------
     |             |               |                 |
 [ Offices ]    [ Rules ]     [ Transport ]       [ Lost ]
     |             |               |                 |
 StaffOffice   RulesIntent    TransportIntent     (links back)


                      [ Fallback Intent ]
                      

🧪 Testing Scenarios
1. Department Query

User: "Where is the computer science department?"
Bot: Gives correct block + floor

2. Event Venue

User: "Where is today's workshop?"
Bot: Provides hall + location

3. Cafeteria Menu

User: "What is available in cafeteria?"
Bot: Shows menu

4. Transport

User: "Where is the bus stop?"
Bot: Gives correct directions

5. Lost Item

User: "I lost my ID card."
Bot: Directs to Admin Office

🚀 Deployment Options

Dialogflow Web Demo

Website chatbot iframe

Mobile app integration

WhatsApp using Twilio

QR Code for easy access

📎Dialogflow Link Here

https://dialogflow.cloud.google.com/#/agent/smart-campus-assistant-478805/intents

📎 GITHUD Link Here

https://github.com/Ankit4981

🏁 Conclusion

The Smart Campus Assistant chatbot enhances communication, improves accessibility, reduces confusion, and acts as a virtual helpdesk for the entire campus.
This project demonstrates strong understanding of AI, NLP, and chatbot development using Dialogflow ES.


