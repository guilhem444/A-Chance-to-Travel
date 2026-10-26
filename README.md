# A Chance to Travel

An AI-powered companion designed to make international student exchange accessible to everyone.

## The Problem

Every year, millions of students consider going on an international exchange, through programs such as Erasmus, TASSEP, MICEFA, or bilateral partnerships. Yet a large number of them give up before they even start.

The main barrier is not a lack of motivation. It is access to information.

Students face a combination of obstacles that, taken together, become overwhelming. Documents are scattered across multiple institutions and websites. Foreign university pages are rarely translated. Deadlines are easy to miss without proper guidance. Financial aid is widely available but largely unknown. And mobility offices can take days to answer even a simple email.

This disproportionately affects students with limited resources, who are the first to abandon their exchange plans. Not because they cannot go, but because they cannot find out how.

With over 7 million students going on international exchange every year, and that number growing, universities need modern tools to support their students through this process.

## Our Solution

**A Chance to Travel** is a browser extension that acts as a personalized AI companion throughout the entire exchange process.

It centralizes and simplifies access to all the administrative information a student needs: visas, housing, scholarships, deadlines, and course equivalencies. It responds instantly, in multiple languages, and adapts to each student's situation.

### For students

Students can ask any question about their exchange and get an instant, personalized answer. The assistant sends automatic reminders before key deadlines, suggests equivalent courses at the host university, translates foreign university pages in real time, and redirects to the right advisor when the question requires human expertise.

### For university mobility offices

Mobility staff can update information through a dedicated back-office interface and access a dashboard showing where students get stuck most, which questions repeat, and which deadlines cause the most drop-offs. This reduces the volume of repetitive emails and frees up time for more complex cases.

### How it works

The assistant is built on a Retrieval-Augmented Generation (RAG) architecture. When a student asks a question, the system searches a document database for the most relevant pieces of information, sourced from mobility hub websites through automatic scraping and manual input by staff. Those documents are passed to a LLM alongside the question, which then generates a precise, context-aware answer based on real and up-to-date data.

This approach ensures the assistant never invents information. It always grounds its answers in verified sources.

### Deployment

The extension activates on mobility-related websites such as MoveOn and university mobility pages, and integrates into existing platforms without requiring any system rebuild.

The first phase is a pilot chatbot widget on university mobility hub pages, fed by the hub's existing data and an automatic scraper. The second phase is a full integration into platform such as MoveOn, the French national student mobility registration platform, with personalized tracking, deadline reminders, and document assistance.

### A dual benefit

Beyond serving students, the assistant generates structured data on where students face the most difficulty. This gives mobility offices actionable insights to improve their communication and support over time, turning the tool into a diagnostic instrument as well as a service.

## Business Model

Our business model is still at an early stage and will need to be developed further. The current direction is a B2B subscription model, where universities and mobility hubs would subscribe to the platform, with pricing adapted to their size, number of partner institutions, and programs offered.

The **intellectual property remains entirely with the team**.

## The Team

We are three students from Paris-Saclay University and Paris-Cité University, and we have all personally experienced an international exchange. That shared experience is what motivated this project in the first place.

| Name | University | Program |
|------|-----------|---------|
| Guilhem Poutrain-Mari | Université Paris-Saclay | Magistère Informatique (CS) |
| Lisa Galan-Sunyach | Université Paris-Cité | Mathematics and CS applied to Economics |
| Jean Dersoir | Université Paris-Saclay | Advanced Biology |

The project was developed as part of the **AI Grand Challenge** organized by Inria and the OECD (GPAI), and was presented at **VivaTech 2026**. Feedback from students, researchers, and industry professionals has shaped the current version of the solution.

## UML Diagrams

Technical documentation is available in the [uml/](./uml/) folder:

[Use case diagram](./uml/01_use_case.md) | [System architecture](./uml/02_architecture.md) | [RAG sequence diagram](./uml/03_rag_sequence.md)

## Sources

See [SOURCES.md](./SOURCES.md) for the full list of references used in this project.
