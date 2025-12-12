Custom Keyboard Development for Refugee Language Accessibility
===================================================

**Student Name(s)**: Kory Singleton   
**Degree and Major**: B.S. in Computer Science  
**Project Advisor Name**: Micheal O'Neil  
**Expected Graduation Date**: May 2026


Problem Statement
-----------------

Many refugee and minority language communities lack access to digital tools that support their native writing systems. While mobile devices are widely available, most operating systems do not include keyboards that support non-dominant or under-resourced languages. As a result, native speakers are unable to read, write, or collaborate digitally in their own language, forcing them to rely on approximations or secondary languages. This limitation significantly hinders literacy efforts, cultural preservation, and collaborative Bible translation work. Without a standardized, Unicode-compliant input method, these communities remain digitally excluded despite having the linguistic knowledge to engage with translated content.


Project Description
-------------------

This project involves the design and development of custom keyboards for Android and iOS that support a refugee community’s native alphabet. The keyboards will allow users to input all required characters, including diacritics and combining marks, in a way that is linguistically accurate and intuitive. The primary use case is to support Bible translation efforts by enabling translators and native speakers to read, write, and collaborate digitally in their own language.

The project emphasizes Unicode compliance, cross-platform compatibility, usability, and long-term sustainability. Open-source tools will be used to ensure low cost and future extensibility. By delivering a fully functional mobile keyboard, this project aims to bridge the gap between technology, language accessibility, and cultural identity.
Java
Swift
XML/JSON


Proposed Implementation Language(s) 
-----------------------------------

Java
Swift
XML/JSON


Libraries, Packages, Development Kits, etc., to be used in the proposed implementation language(s)
--------------------------------------------------------------------------------------------------


Android SDK
Keyman Developer
Unicode Standard libraries


Additional Software/Equipment Needed
------------------------------------

Android Studio
Xcode
Git/Github
Android Smartphone/tablet


Alternative Solutions and Rationale 🔍
--------------------------------------

### Alternative 1: Custom Font with Standard Keyboard
- **Description**:  
  Create a custom front that maps the refugee langauge characters to existing ASCII keys using a standard keyboard
- **Pros**:  
Quick to implement
Minimal platform-specific development

- **Cons**:  
Text breaks when shared across devices
Not compatible with translation software
Unsustainable long-term

### Alternative 2: Web-Based Input Tool
- **Description**:  
Develop a browser-based text input tool that allows users to type using a custom on-screen keyboard.
- **Pros**:  
 Platform indepedent
Easier deployment and updates
- **Cons**:  
  Requires constant internet access
  Not integrated with mobile OS input systems

### Chosen Solution and Rationale
- **Chosen Solution**:  
Native Android and iOS keyboards built using Unicode-compliant layouts and open-source keyboard frameworks.
- **Rationale**:  
This approach provides full integration with mobile operating systems, ensuring the keyboard works across all applications. Unlike font-based or web-only solutions, native keyboards offer better usability, offline functionality, long-term sustainability, and compatibility with translation tools. While development effort is higher, the resulting solution is more scalable, accessible, and culturally appropriate.


Personal Motivation
-------------------

I am motivated to pursue this project because it combines technical problem-solving with meaningful real-world impact. Language is deeply tied to identity, and the lack of digital support for refugee languages creates an unnecessary barrier to communication and literacy. As a computer science student and especially as a minority, I want to apply my skills to projects that serve underrepresented communities. This project also aligns with my interest in accessibility, open-source development, and building software that addresses cultural and humanitarian needs.

Outline of Future Research Efforts
----------------------------------

To complete this project, the following research and preparation tasks are required:

Study Unicode encoding practices for minority scripts

Learn platform-specific keyboard APIs for Android and iOS

Research best practices for diacritic and combining mark input

Consult linguistic documentation to verify script rules

Evaluate usability standards for mobile input systems

Schedule 📅
-----------

> Update the dates and add your tasks by replacing the examples. Remove this note.

*   Spring 2026 - CSCI 497
    -   January 26 -  February 9 - Finalize project scope and proposal
    -   February 23 - Complete initial research  
    -   March 8 - Draft keyboard layouts and character mappings
    -   March 22 - Send First-Draft of the Requirements Document to advisor for feedback
    -   April 5 - Revise requirements and finalize technical plan

*   Summer 2040 - Independent/Optional Project Work
    -   June 1 - Begin early prototyping and tool familiarization

*   Fall 2026 - CSCI 498
    -   October 20 - Implement android keyboard prototype
    -   October 27 - implement ios keyboard prototype
    -   November 3 - integrate advanced character handling
    -   November 10 - conduct internal testing on emulators and devices
    -   November 17 - collect preliminery user feedback
    -   November 20 - refine implementation based on feedback

*   Spring 2027 - CSCI 499 (more details will be added here once you are closer)
    -   Weeks 1-4 - Implement test plan
    -   Week 5 - Evaluate test results
    -   Week 6-10 - Apply updates and bug fixes based on the results
    -   Week 8 - Complete the first 4 chapters of the defense documentation.
    -   Final weeks: prepare final presentation and submission


References 📚
-------------
