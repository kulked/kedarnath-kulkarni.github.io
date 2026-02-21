# AI-Powered Auto-Fix for SMB Advertisers @ Microsoft
**Focus:** AI/ML Product Management, Growth, & Policy Enforcement

## 🚀 The Impact (TL;DR)
* **North Star Metric:** Target an **80% Accelerated Fix Rate** (ads approved within 2 hours of rejection).
* **Business Value:** Unlocks a portion of **$12B in annual revenue** by reducing churn for the SMB segment (60% of accounts).
* **Technical Edge:** Leverages **Copilot (LLMs)** to transform opaque policy rejections into actionable, compliant copy suggestions.

---

## 🔍 Context & Problem
Microsoft Advertising manages a high-scale ecosystem (Search, Gaming, Retail Media) where **Trust & Safety** is a fundamental pillar. 

### The Pain Point
While enterprise clients have policy experts, **Small and Medium Businesses (SMBs)** often face "vague rejections" that lead to multi-day campaign holds and lost revenue.
* **Original Content:** "We have no idea what policy we have violated and do not know what to fix." - *User Feedback*.
* **Proposed Enhancement (Strategic Framing):** Reframe this not just as a support issue, but as a **conversion funnel problem**. Every hour an ad is rejected is an hour of "lost inventory monetization."

---

## 🛠 Product Strategy & Technical Logic
I prioritized the **SMB segment** because they represent the majority of Microsoft's accounts and lack the resources to navigate complex policy manuals.

### Solution: The Auto-Fix Workflow
Instead of a generic rejection, the system provides a **Rejection Insight Panel** with one-click remediations.

#### [Technical Edge] Proposed Model Logic (LLM Architecture)
To demonstrate technical depth, the portfolio explains the internal "Prompt & Verify" loop:
1. **Input:** Disapproved ad creative + Triggered Policy (e.g., Clickbait).
2. **LLM Prompt:** "Rewrite this headline to remove sensationalism while maintaining a 0.8+ semantic similarity to the original intent."
3. **Verification:** The "Policy Risk Score" ensures the new suggestion won't trigger a secondary violation (e.g., Adult content).

---

## 🗺 Roadmap: From MVP to Scale
| Phase | Focus Area | Key Features |
| :--- | :--- | :--- |
| **Now (MVP)** | Foundational Clarity | Rejection Insight Panel & URL Compliance Checker. |
| **Next** | Content Generation | AI Clickbait Detection & Auto-Rewrite Suggestions. |
| **Later** | Advanced Assets | Copilot Remediation Chat & AI fixes for Video/Images. |

---

## 📊 Measuring Success
I defined a tiered metric structure to ensure the AI creates real value without "gaming" the system.

* **P0 (Adoption):** % of SMBs adopting the auto-fix flow.
* **P0 (Accuracy):** % of suggested fixes approved on first resubmission (Goal: $\ge80\%$).
* **Counter-Metric:** **Re-rejection Rate.** Track if bad actors try to "reverse-engineer" policies through repeated AI prompts.

---

## 💡 Proposed Improvement: "Human-in-the-Loop"
**Original Content:** Focuses on the automated AI pipeline and human appeals for false positives.
**Proposed Content:** Add a section on **"Reinforcement Learning from User Feedback (RLHF)."** Explain how SMB "up-votes" on AI-generated headlines are fed back into the model to improve the tone and effectiveness of future suggestions.
