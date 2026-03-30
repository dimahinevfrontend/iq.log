
# Project Brief: ArchitectHub (The Post-Code Professional Network)

## 1. Vision & Core Concept
**ArchitectHub** is a minimalist professional ecosystem designed for the AI era. Since AI now handles code execution, this platform shifts the focus to **Human Insight, System Architecture, and Strategic Leadership**. It prioritizes high-value experience sharing over vanity metrics.

---

## 2. Design Philosophy
* **Visual Style:** "Terminal Minimalism" / Bento Grid layout.
* **Theme:** Deep Dark Mode by default (High contrast, #000000 or #0D1117 backgrounds).
* **Typography:** Monospace fonts for data/metrics; clean Sans-Serif for long-form insights.
* **UI Principles:** Zero ads, zero "success-porn" fluff, 1px borders, 4px border-radius.

---

## 3. Dashboard Layout (3-Column Grid)

### A. Left Column: Identity & Visibility (Narrow)
* **Human Value Score (HVS):** A prominent numerical rank based on community validation.
* **Visibility Meter:** A real-time gauge showing your current ranking in recruiter search results.
* **Skill Wisdom:** High-level tags (e.g., `System Design`, `AI Orchestration`, `Ethical Scaling`)—each must be backed by a post.

### B. Center Column: The Insight Stream (Wide)
The "Heart" of the platform. Instead of "posts," users publish **Insight Logs**:
* **Decision Logs:** Why a specific architecture was chosen.
* **Post-Mortems:** Deep dives into failures and lessons learned.
* **AI Strategies:** How AI agents were orchestrated to solve a business problem.
* **Format:** Full Markdown support with integrated diagramming tools (Mermaid.js).

### C. Right Column: Market & Growth (Medium)
* **Verified Offers:** A feed of incoming job opportunities.
* **Transparency Wall:** Recruiters **cannot** message without filling out:
    * Annual Compensation Range (USD/EUR).
    * Specific Problem to Solve (not just a "job description").
    * Remote/On-site status.
* **Mentorship Slots:** Active status for coaching others (boosts visibility).

---

## 4. Engagement-Driven Visibility (The Algorithm)

The platform eliminates "pay-to-play" for recruiters. Search results are governed by **Community Karma**.

| Action | Impact | Logic |
| :--- | :--- | :--- |
| **"Insightful" (Like)** | +1 Karma Point | Peer validation of a shared idea. |
| **Meaningful Comment** | +3 Karma Points | Active contribution to professional discourse. |
| **High-Rank Endorsement** | +10 Karma Points | When a Top-10% Architect validates your post. |
| **Inactivity** | Karma Decay | Slight reduction over time to keep the leaderboard fresh. |

**The Result:** Your position in the Recruiter Search UI is calculated as:  
$$Ranking = \text{Total Karma} \times \text{Recency Factor}$$

---

## 5. Implementation Roadmap (MVP)

| Phase | Focus | Deliverable |
| :--- | :--- | :--- |
| **1. The Hub** | Core Layout | Responsive 3-column dashboard with Markdown editor. |
| **2. Karma Engine** | Logic Layer | DB schema for tracking Karma and real-time ranking. |
| **3. Talent Portal** | Recruiter UI | Search interface sorted by Karma with mandatory "Offer Form." |
| **4. Visual Proof** | Diagramming | Integration of Mermaid.js for architectural visualization. |

---

## 6. Risks & Unknowns
* **Risk:** Users might attempt "Engagement Pods" to artificially boost Karma.
* **Mitigation:** Implement weighted voting (votes from high-karma users count more).
* **Unknown:** How to balance the ranking so new talented users can climb the leaderboard quickly.


Домен – iqlog.sh