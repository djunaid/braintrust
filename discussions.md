<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Discussion](#discussion)
  - [Design Decisions (Reasoning)](#design-decisions-reasoning)
    - [Points System (Why? Structure? Give users info about Points)](#points-system-why-structure-give-users-info-about-points)
    - [User Help (Pop-up information & Mouseovers)](#user-help-pop-up-information--mouseovers)
    - [Leaderboard & Weighting of Points](#leaderboard--weighting-of-points)
      - [Why have users compete with eachother?](#why-have-users-compete-with-eachother)
    - [Include User Profile Photo (Why? Where?)](#include-user-profile-photo-why-where)
    - [Amendments (Why?)](#amendments-why)
    - [PDCA (Why?)](#pdca-why)
  - [Potential Problems](#potential-problems)
    - [[Problem 1] Management bottleneck w.r.t. processing ideas](#problem-1-management-bottleneck-wrt-processing-ideas)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Discussion
The purpose of this document is to outline design decisions as well as some potential problems with respect to Braintrusts eIDEAS project. This document attempts to answer the _why_ questions new readers may have.


## 1 Points System
The primary function of the point system is to provide some rewards for collaborating. In addition the point system provides various types of motivations which incentivize users to return.
### 1.1 Motivation
#### 1.1.1 Users are motivated by earning physical rewards
#### 1.1.2 Flexibility to Managers w.r.t. setting rewards
#### 1.1.3 Users are motivated by progression
#### 1.1.4 Users are motivated by competition
#### 1.1.5 Easy to track progress goals (Upper Management)
### 1.2 Structure
#### 1.2.1 Idea Points
#### 1.2.2 Participation Points
#### 1.2.3 Reasoning
#### 1.2.4 Potential Problems
To compensate for varying team size, points must be scaled accordingly.
### 1.3 Info about Points
Users are provided information about points 
## 2 Page Design
### 2.1 Login
### 2.2 Registration
### 2.3 Homepage
#### 2.3.1 About eIDEAS pop-up
### 2.4 Leaderboard
### 2.5 My Team
#### 2.5.1 Tracking Ideas
### 2.6 My Ideas
#### 2.6.1 Scoring Ideas
### 2.7 Account
### 2.8 Contact Us
### 2.9 Admin
## 2 User Help
### 2.1 Pop-up information
### 2.2 Mouseovers
## 3 Leaderboard & Weighting of Points
### 3.1 Why have users compete with eachother?
## 5 Include User Profile Photo (Why? Where?)
## 6 Amendments (Why?)
## 7 PDCA/PDEA (Why?)
## X Other Ideas
### User Badges

## 8 Potential Problems

### 8.1 [Problem 1] Management bottleneck w.r.t. processing ideas

**Description:** Managers may be overburdened by the amount of ideas they have to process if they must move the PDCA status for every idea for each team they manage.

**Suggestions:**
  1. Allow all users to move the PDCA status with no restrictions.
      * **Pros:** Manager will be completely burden-free as any user can progress the PDCA cycle.
      * **Cons:** If every user can progress an idea along then there will be users who abuse the system to maximize their points. For example, create "dummy" idea and move it to completion instantly in order to collect points.

  2. Emphasize somewhere (e.g. About eIDEAS pop-up on homepage) that Managers are not required to process every single idea submitted. Suggest that they process some number of ideas per week (e.g. 5 per week). These ideas can be selected at the Manager's discretion (e.g. choose "top ideas" as ranked by Score).
      * **Pros:** The load on Manager is lightened as they are not obligated to process every single idea. In addition, Managers have some choice w.r.t. which ideas should (or can) be completed first.
      * **Cons:** By not requiring every idea to be processed, some ideas may be forgotten. The suggested "ideas per week" is a number that must be selected carefully --- too high and the Manager is overburdened; too low and ideas may not see any progression (i.e. they get "stuck" in the queue).

  3. Managers can designate another user from their team (or multiple if they are part of more than one team) to act on their behalf to move the PDCA status. This should be limited to team size in order to avoid (1) above. For example, a manager can assign 1 delegate per 10 members of their team (i.e. team size of 10 -> 1 delegate, team size of 20 -> 2 delegates, etc).
      * **Pros:** This distributes the work load across multiple people, therefore lowering the burden of the Manager. This also avoids the problem of (1) where users can abuse the system via "dummy" ideas.
      * **Cons:** The amount of delegates per team should be selected carefully --- too many delegates may lead to abuse of the points system; too few and the work load is not adequately distributed. Assigning delegate(s) is itself work, so it is another thing Managers have to do.

**Recommendations:**

Use a combination of (2) and (3). Start with (2) and observe the suggested "ideas per week" number. If the Manager cannot process this number of ideas per week such that the amount of "forgotten"/"stuck" ideas is minimal, use (3) and introduce delegates.

This recommendation overcomes the problems of (1), while also solving the Manager bottleneck issues. For most teams (small), suggestion (2) might be sufficient. If (2) is not sufficient (e.g. for large teams), adding delegates from (3) provides flexibility to mitigate potential "forgotten"/"stuck" ideas that may be introduced by (2).
