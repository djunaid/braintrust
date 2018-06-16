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
| FR1-1 | The system shall allow the user to enter a new idea.   |
| FR1-2 | The system shall allow the user to edit/update their own ideas.   |
| FR1-2.1 | The system shall allow the user to add comments (if any) to an idea.   |

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
| FR3-2 | The system shall allow the user to view unsuccessful ideas from the past.   |
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
| FR5-1 | The system shall allow the user to log into their account.   |
| FR5-1.1 | The system shall allow the user to create an eIDEAS account.   |
| FR5-1.2 | The system shall allow the user to authenticate with their eIDEAS username and password.   |
| FR5-1.3 | The system shall display a "forgot password" link closely in proximity to the login button.   |
| FR5-1.3.1 | The system shall take the user to a forgot password page after clicking the "forgot password" link.   |
| FR5-2 | The system shall have a home page presented after logging in.   |
| FR5-2.1 | The system's home page shall have a tabular navigation bar.   |
| FR5-2.2 | The system's home page shall display graphical 2D statistics about ideas (see FR4-1.1).   |
| FR5-2.3 | The system's home page shall display a small paragraph about eIDEAS (via pop-up).   |
| FR5-2.4 | The system shall have a "Contact Us" page link in the tabular navigation.   |
| FR5-2.4.1 | The "Contact Us" page shall display name, email, message field, and a submit button.   |

#### Table 6: Idea PDCA Progression
| ID     | Requirement Definition     |
| :--- | :--- |
| FR6-1 | The system shall allow the user (manager) to change the PDCA phase of ideas within their team(s).   |


## 4 Other Requirements
The application should be "user-friendly" and easy to maintain.

### 4.1 Interface Requirements
The interface should be web based (Vue.js) and mobile device friendly.

#### 4.1.1 Software Interfaces
Some kind of web stack (e.g. LAMP), using Vue.js.
