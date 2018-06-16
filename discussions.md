# Discussion
The purpose of this document is to outline some potential problems with respect to eIDEAS design decisions and discuss potential solution alternatives.

TODO: Table of Contents to navigate problems quickly.

## Design Decisions (Reasoning)
### Points System (Why? Structure? Give users info about Points)
### User Help (Pop-up information & Mouseovers)
### Leaderboard & Weighting of Points
#### Why have users compete with eachother?
### Include User Profile Photo (Why? Where?)
### Amendments (Why?)
### PDCA (Why?)

## Potential Problems

### [Problem 1] Management bottleneck w.r.t. processing ideas

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

Use a combination of (2) and (3). Start with (2) and observe the suggested "ideas per week" number. If the Manager cannot process this number of ideas per week such that the amount of "forgotton"/"stuck" ideas is minimal, use (3) and introduce delegates.

This recommendation overcomes the problems of (1), while also solving the Manager bottleneck issues. For most teams (small), suggestion (2) might be sufficient. If (2) is not sufficient (e.g. for large teams), adding delegates from (3) provides flexibility to mitigate potential "forgotten"/"stuck" ideas that may be introduced by (2).
