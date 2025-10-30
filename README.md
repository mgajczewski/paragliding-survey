# 🪂 Paragliding Survey Templates

A collection of ready-to-use **templates** for creating surveys and feedback forms used in **paragliding** - whether for competitions, clubs, or pilot communities.

## ✈️ Purpose

The main goal of this project is to create a collaborative workspace for developing survey templates and gathering feedback about them.  
The resulting templates can be adapted and used in various formats:
- Printed paper surveys
- Online forms

## 📋 Available Templates

| Template | Description | Version History |
|------|-------------|-----------------|
| `ballast-fairness-survey` | Ballast & Fairness in Paragliding Competition | [View](ballast-fairness-survey/VERSION_HISTORY.md) |

## 🤝 Contribution and workflow

We warmly welcome contributions as approvers or Pull request creators! The Pull request approval rules will be enforced once we have more than 3 approvers in the community.

- **Reporting feedback**: please use GitHub Issues. Every reported problem or proposal will receive the appropriate label according to the repository's label list: [Labels](https://github.com/mgajczewski/paragliding-survey/labels).
- **Voting on proposals**: for issues labeled as **enhancement** or **redesign**, please add your vote using reactions (👍 for support, 👎 for opposition). Your votes matter and determine whether proposals move forward!
- **Contributing**: feel free to create Pull requests or review existing ones. Your input is highly appreciated!

### 🏷️ Label-specific workflow

- **correction**: text/link fixes are applied immediately after the Pull request is approved by 1 reviewer.
  - Requirements: the Pull request must reference the related issue and obtain at least 1 approval.

- **enhancement**: new features/improvements require initial community support.
  - Decision: the issue must receive at least 3 👍 (reactions) before we start implementation.
  - Pull request: at least 1 approval is required before merge.

- **redesign**: larger changes to questions or survey structure.
  - Decision: 3 days (72 h) after the issue is created, the number of 👍 vs 👎 determines whether we proceed (if 👍 > 👎, we continue; otherwise it goes back for refinement/gets closed).
  - Pull request: 3 approvals are required before merge.

### ✅ Voting and reactions

- We use GitHub reactions for voting: 👍 as “like”, 👎 as “dislike”.
- Only reactions added to the issue description (first post) are counted.

### 🔀 Pull Requests – guidelines

- One Pull request should address only one issue, nothing more, and include a reference to the issue number.
- Pull request title: include the label and the issue number, e.g., `Issue 12: Add FAQ section`.


## 🚀 Example

```markdown
# 🪂 Competition Feedback Form

**Competition name:**  
**Location & date:**  
**Task number:**  

### 🏁 Task
- How would you rate the task design (1–5)?  
- Was the task appropriate for the conditions?  
- Any suggestions for improvement?

### 🧭 Organization
- Takeoff logistics:  
- Safety briefings:  
- Retrieve efficiency:  

### ⚠️ Safety
- Any incidents or close calls?  
- Did you feel pressured to fly beyond comfort zone?

### 💬 Additional comments
- ...
```