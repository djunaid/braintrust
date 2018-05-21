# Functional Requirements

## 1 Introduction
The system requested by eHealth with the goal to improve the quality of healthcare  across the province. This follows the organization's ongoing efforts to foster an internal culture of innovation. Using Plan, Do, Check, Act (PDCA) cycles the goal is to improve quality, cost, delivery, safety, and engagement (QCDSE).

The proposed project accomplishes this by providing and application for employees to submit their ideas for improving existing organizational processes.  This increases visibility of individual and collaborative work.

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
| FR1-1 | The system shall allow the user to enter an idea.   |
| FR1-1.1 | The system shall allow the user to enter an idea.   |
| FR1-2 | The system shall allow the user to edit/update their own ideas.   |

#### Table 2: Viewing Ideas
| ID     | Requirement Definition     |
| :--- | :--- |
| FR2.0 | The system shall allow the user to view their own ideas.   |
| FR2.1 | The system shall allow the user to view other users ideas.   |
| FR2.2 | The system shall allow the user to view the PCDA status of a current idea.   |

#### Table 3: Searching/Filtering Ideas
| ID     | Requirement Definition     |
| :--- | :--- |
| FR3.0 | The system shall allow the user to view successful ideas from the past.   |
| FR3.1 | The system shall allow the user to view unsuccessful ideas from the past.   |

#### Table 4: Viewing Statistics of Ideas
| ID     | Requirement Definition     |
| :--- | :--- |
| FR4.0 | The system shall allow the user to view some graphical statistics about ideas.   |
| FR4.1 | The system shall allow the user to view the total number of submitted ideas.   |

## 4 Other Requirements
The application should be "user-friendly" and easy to maintain.

### 4.1 Interface Requirements
The interface should be web based (Vue.js) and mobile device friendly.

#### 4.1.1 Software Interfaces
Some kind of web stack (e.g. LAMP), using Vue.js.