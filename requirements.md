<!-- START doctoc generated TOC please keep comment here to allow auto update --> 
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Functional Requirements](#functional-requirements)
  - [1 Introduction](#1-introduction)
    - [1.1 Purpose](#11-purpose)
    - [1.2 Scope](#12-scope)
    - [1.3 References](#13-references)
    - [1.4 Assumptions](#14-assumptions)
  - [2 Methodology](#2-methodology)
  - [3 Functional Requirements](#3-functional-requirements)
      - [Table 1: Creating/Updating Ideas](#table-1-creatingupdating-ideas)
      - [Table 2: Viewing Ideas](#table-2-viewing-ideas)
      - [Table 3: Searching/Filtering Ideas](#table-3-searchingfiltering-ideas)
      - [Table 4: Viewing Statistics of Ideas](#table-4-viewing-statistics-of-ideas)
      - [Table 5: Home Page/Login/Contact Us](#table-5-home-pagelogincontact-us)
      - [Table 6: Idea PDEA Progression](#table-6-idea-pdca-progression)
  - [4 Other Requirements](#4-other-requirements)
    - [4.1 Interface Requirements](#41-interface-requirements)
      - [4.1.1 Software Interfaces](#411-software-interfaces)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Functional Requirements

## 1 Introduction
The system requested by eHealth with the goal to improve the quality of healthcare  across the province. This follows the organization's ongoing efforts to foster an internal culture of innovation. Using Plan, Do, Check, Act (PDEA) cycles the goal is to improve quality, cost, delivery, safety, and engagement (QCDSE).

The proposed project accomplishes this by providing and application for employees to submit their ideas for improving existing organizational processes.  This increases visibility of individual and collaborative work.

**Notice:** **P**lan **D**o **C**heck **A**ct has been substituted by **P**lan **D**o **E**valuate **A**dapt. See [Discussion](./discussions.md) document.

### 1.1 Purpose
The purpose of this document is to provide a backbone reference for the development of the eIDEAS project. The below sections are intended to provide a list of specific functional requirements that can lead to a minimum viable product.

### 1.2 Scope
The scope of this document is to provide enough information to the group so that they have a good starting point for their work during Phase 2.

### 1.3 References
Refer to [UR Courses](https://urcourses.uregina.ca)  project requirement documentation.

### 1.4 Assumptions
 * The project will be under MIT license.
 * Balsamiq is used to creating mockup screens.
 * Vue.js will be used.
 * Source code and related documents will be hosted on a public GitHub.

## 2 Methodology
Using Balsamiq, mockups for the envisioned project were created. Each mockup screen helps to identify a piece of the functionality for the whole project.

TL;DR
Take mockups and break them down into individual requirements (1 sentence each), then put them into a table.

## 3 Functional Requirements

#### Table 1: Creating/Updating Ideas
| ID     | Requirement Definition     |
| :--- | :--- |
| FR1-1 | The system shall allow the user to enter a new idea.   |
| FR1-2 | The system shall allow the user to edit/update their own ideas.   |
| FR1-2.1 | The system shall allow the user to add amendments to an idea.   |

#### Table 2: Viewing Ideas
| ID     | Requirement Definition     |
| :--- | :--- |
| FR2-1 | The system shall allow the user to view their own (as well as others) ideas.   |
| FR2-1.1 | Each idea shall display (at minimum) the following information: submitter name, team, idea title, idea description, ~~"tags"/affecting areas~~, idea creation time, (PCDA) status.   |
| FR2-2 | The system shall allow the user to view the PCDA status of a current idea.   |

#### Table 3: Searching/Filtering Ideas
| ID     | Requirement Definition     |
| :--- | :--- |
| FR3-1 | The system shall allow the user to view successful ideas from the past.   |
| FR3-2 | The system shall allow the user to view unsuccessful (abandoned) ideas from the past.   |
| FR3-3 | The system shall allow the user to filter ideas on any field from FR2-1.1.   |

#### Table 4: Viewing Statistics of Ideas
| ID     | Requirement Definition     |
| :--- | :--- |
| FR4-1 | The system shall allow the user to view some graphical statistics about ideas.   |
| FR4-1.1 | The system shall store some statistics about the fields in FR2-1.1 as needed.   |
| FR4-2 | The system shall allow the user to view the total number of (global) submitted ideas.   |

#### Table 5: Home Page/Login/Contact Us
| ID     | Requirement Definition     |
| :--- | :--- |
| FR5-1 | The system shall allow the user to log into their eIDEAS account.   |
| FR5-1.1 | The system shall allow the user to create an eIDEAS account.   |
| FR5-1.2 | The system shall allow the user to authenticate with their eIDEAS username and password.   |
| FR5-1.3 | The system shall display a "forgot password" link closely in proximity to the login button.   |
| FR5-1.3.1 | The system shall take the user to a forgot password page after clicking the "forgot password" link.   |
| FR5-2 | The system shall have a home page presented after logging in.   |
| FR5-2.1 | The system's home page shall have a tabular navigation bar.   |
| FR5-2.2 | The system's home page shall display graphical 2D statistics about ideas (see FR4-1.1).   |
| FR5-2.3 | The system's home page shall display a small paragraph about eIDEAS (via pop-up on the homepage).   |
| FR5-2.4 | The system shall have a "Contact Us" page link in the tabular navigation.   |
| FR5-2.4.1 | The "Contact Us" page shall display name, email, message field, and a submit button.   |

#### Table 6: PDEA Management
| ID     | Requirement Definition     |
| :--- | :--- |
| FR6-1 | The system shall allow the user (via management page) to change the PDEA status of an idea for their respective team(s).   |
| FR6-2 | The system shall provide a drop-down menu to select Plan/Do/Evaluate/Adapt/Abandon/Complete statuses for an idea.   |
| FR6-2.1 | After selection of each Plan/Do/Evaluate/Adapt/Abandon/Complete status a pop-up confirmation message will be presented.   |
| FR6-2.1.1 | After selecting the Adapt status the system shall allow the user to type in an updated plan. This plan should reflect adaptations discovered in the Evaluation phase.   |
| FR6-2.1.2 | After selecting the Abandon status the system shall allow the user to type in a reason for abandonment.   |
| FR6-2.2 | The drop-down menu shall enforce the correct PDEA flow (e.g. P->D->E->A).   |
| FR6-2.3 | The 'Complete' status shall only be available after the 'Evaluate' phase.   |
| FR6-2.4 | The 'Abandon' status shall be available at any phase.   |

## 4 Other Requirements
The application should be "user-friendly" and easy to maintain.

### 4.1 Interface Requirements
The interface should be web based (Vue.js) and mobile device friendly.

#### 4.1.1 Software Interfaces
Some kind of web stack (e.g. LAMP), using Vue.js.
