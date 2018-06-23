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
The motivations for choosing a points system are described below.

#### Users are motivated by earning physical rewards
This is one of the strongest motivators for users. Motivation is strongly correlated with the quality of the physical reward. For example, a new car is more motivating than a new water bottle.
#### Users are motivated by progression
Users like seeing themselves improve. Having a point system allows users to see how they are progressing compared to their past selves. If they are improving, they will be happy with themselves. If they are not improving, they might find this fact as a decent motivator.
#### Users are motivated by competition
Competition can also be a strong motivator. Many people like comparing themselves to others because it shows the potential gap between them. If there is a gap, there is room for improvement. If there is room for improvement, people will tend to seek it out.
#### Flexibility to Managers
Managers have flexibility with a point system because the points and rewards themselves can be chosen arbitrarily. For example, managers can select a range of points over time in order to evenly distribute physical rewards while still respecting a budget. This allows the "reward path" to be shaped from the budget and not the other way around.
#### Easy to track Organizational Progress
This is primarily a benefit for Upper Management. Having a point system implies many statistics and metrics about points are already being tracked. This makes it trivial for Upper Management to receive a report out regarding progress. Number of ideas, rate of improvement (individual & team), rate of failure, top contributors, and many others are examples of things that are implicitly tracked.

### 1.2 Structure
The structure of the point system provides two ways of measuring progress. The first way is **Idea Points**, which corresponds directly to progression of ideas themselves. The second way is **Participation Points**, which corresponds to user engagement.
#### Idea Points
Idea Points are collected by users each time an idea is submitted or completed. These are the "primary currency" with respect to rewards, and as such, are harder to obtain. Being harder to obtain necessitates greater rewards, so managers must mindful of this.
#### Participation Points
Participation Points are collected by users each time they engage with an idea in the system. These are the "secondary currency" with respect to rewards, and are easier to obtain than Idea Points. Therefore, rewards for Participation Points should be lesser, but more frequent to promote consistent user engagement. Users may obtain Participation Points by engaging in any action regarding an idea. These actions can be (but are not limited to): scoring an idea, adding an amendment to an idea, creating an idea, moving an idea through it's phases (i.e. PDCA/PDEA).
#### Reasoning
Splitting points into two types provides some advantages. Some users may not be as creative as others, so they may not be able to accumulate as many Idea Points. Participation Points give these users a stable way to receive rewards by still providing contributions to the system. Further, having Idea Points to measure the creation and completion of ideas is a straightforward way to track the primary goals of the system.
#### Potential Problems
To compensate for varying team size, points must be scaled accordingly. For example, if normalization is not used, large teams will surely dominate as they have more potential to generate ideas. To allow for a meaningful comparison with respect to teams, each team's cumulative points must be scaled by the size of the team. This is a non-perfect solution, but should work well enough to provide users with competitive motivations. It is important to have meaningful comparisons in competition in order to promote team work.

Normalization is not needed for the individual since comparing individuals is straightforward.
### 1.3 Other Information about Points
Users are provided information about points in various places in the eIDEAS system. Once place is the "About eIDEAS" pop-up that displays when a user first logs into the system. Other places have yet to be determined, but there certainly should be a central area that explains to the user how to earn points, how many points an action rewards, and how many points the user has accumulated as well as their "reward track".

The structure of points will be decided by Administrators via the tools on the Admin page. This will be where exact point values for each action will be entered.
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
