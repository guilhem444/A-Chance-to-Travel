# Roadmap

A Chance to Travel is currently at the design stage. We have no code yet, but we have a detailed and structured vision of what we want to build and how we want to get there. This roadmap reflects our current thinking and will evolve as the project moves forward.

## Where we are now

We have defined the problem, designed the architecture, identified the key features for both students and mobility offices, and documented everything in this repository. The technical choices (RAG architecture, browser extension, B2B model) are in place. What comes next is turning this into a real product.

## Phase 0 : Design and validation (current)

The goal of this phase is to validate our assumptions before writing a single line of code.

This includes conducting interviews with students who have been on or considered an international exchange, meeting with university mobility offices to understand their actual workflows and pain points, validating the technical architecture with people who have built similar tools, and refining the business model based on real feedback from potential institutional partners.

We also want to identify a first partner university willing to pilot the tool, as this will shape every subsequent decision.

## Phase 1 : Prototype

Once the design is validated, the first step is to build a minimal working version of the assistant.

This means setting up the RAG pipeline with a small document base (one university, one program), building a basic chat interface as a browser extension, and connecting it to a real mobility hub's data, even in a limited and manual way. No back-office yet, no dashboard, no notifications. Just a student asking a question and getting a useful, grounded answer.

The goal is to test the core assumption: does the RAG approach actually produce reliable and helpful answers in the context of student mobility?

## Phase 2 : Pilot

With a working prototype, the next step is to deploy it with a small group of real students at one partner university.

This phase introduces the student account system, deadline reminders, and a basic back-office interface for mobility staff to update information. We collect structured feedback from both students and staff, monitor where the assistant fails or gives incomplete answers, and iterate quickly.

The dashboard that shows where students get stuck most will also be built during this phase, as it requires real usage data to be meaningful.

## Phase 3 : Integration with MoveOn or on another platform

MoveOn is the main platform French universities use to manage student exchange applications. Integrating with it would allow the assistant to access real-time application data for each student and provide truly personalized guidance but it is also applicable to another platform as long as this platform has enough data/information on the program and exchanges.

This phase depends on reaching an agreement with the platform's operators, which is why we have not yet initiated that process. It is a medium-term goal that requires institutional trust and data access agreements.

## Phase 4 : Expansion

Once the tool is proven in a university context, the next step is to expand to other national systems.

This includes adapting the document base and scraper to non-French university websites, supporting more exchange programs, and exploring partnerships with international mobility networks.
