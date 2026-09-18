# Demo notes — Copilot code review on a pull request

## Talk track

1. **Where the review gets requested.** On the pull request page, in the right sidebar under **Reviewers**, Copilot is listed alongside human reviewers. Clicking **Request** next to Copilot adds it as a reviewer.
2. **How long it takes.** Copilot's review usually completes in **under 30 seconds**.
3. **What comes back.** Copilot leaves a **Comment** review — not "Approve" or "Request changes" — with inline comments on specific lines. Each comment is tagged **High**, **Medium**, or **Low** severity so the author can prioritise.
4. **What to do with it.** Comments behave like human review comments: react, reply, resolve. Comments you add are visible to humans but **not** to Copilot, and Copilot will not reply. Where possible, feedback arrives with suggested changes that can be applied in a couple of clicks.
5. **A few caveats.** By default Copilot does not re-review automatically when you push new commits — you have to re-request. Reviews can be made automatic for every PR, and custom instructions can steer them (`.github/copilot-instructions.md`).

## Talking points for Q&A

- Does Copilot's review count as an approval? No — not by default. Approvals can be enabled by an enterprise/organization administrator or repository administrator.
- Can the thoroughness be tuned? Yes — a review effort level of **Lite** or **Balanced** can be selected before requesting the review.
- Is it available without a Copilot license? For organization members, yes, when enabled by an enterprise administrator or organization owner.
