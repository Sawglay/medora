# Medora — AI-Assisted Hospital Administration

Medora is an academic web application that helps patients prepare registration forms, find doctors, and manage appointments. It combines a conversational interface, structured hospital records, and a knowledge graph to support administrative tasks.

The project includes a **patient portal**, a **staff dashboard**, and a **server-side API with persistent storage**.

> **Prototype status:** The current application uses fictional hospital data. Graph-backed guided chat is available. Live GPT responses require a server-side OpenAI API key. The prototype does not provide medical diagnosis or treatment advice.

## Demo

The hosted demo is private and requires an authorized ChatGPT account. Adding this link to a public GitHub repository does not make the demo publicly accessible.

## Project Objective

Hospital registration and appointment processes often involve repeated questions, incomplete forms, and information spread across different systems. Medora brings these administrative tasks into one website.

The project investigates the following research question:

> Can combining conversational understanding with structured hospital information provide more reliable administrative assistance than a standalone chatbot?

The proposed research method combines a literature review with prototype evaluation. Comparative model results have not yet been collected.

## Key Features

### Patient Portal

- Create and edit a patient registration profile.
- Validate required details and request consent before saving.
- Prepare a checklist of identification, insurance, referral, and guardian documents.
- Search fictional doctors and filter by department.
- View available appointment slots for the next 14 days.
- Review and confirm appointment details before booking.
- Reschedule or cancel confirmed appointments.
- Download appointment summaries in JSON format.
- Ask the assistant about registration, documents, departments, and appointments.
- Use English or Thai patient navigation and administrative responses.

### Staff Dashboard

- View registration and appointment summaries.
- Review patient registrations and record administrative notes.
- Mark registrations as pending, reviewed, or requiring changes.
- Manage doctor details and availability.
- Close or reopen appointment slots.
- Check in patients and mark visits as completed.
- Create and edit knowledge graph entities and relationships.
- Review server activity and export structured information.

