# copilot-review-demo-2

This repository is a live sandbox for a team show-and-tell on **GitHub Copilot code review**.

## What it demonstrates

- A branch (`demo-tweak`) with a small change, opened as a pull request into `main`.
- Requesting a review on that pull request from GitHub Copilot (Copilot appears as a reviewer in the **Reviewers** section of the PR sidebar).
- Reading Copilot's feedback: inline review comments, each tagged with a severity of **High**, **Medium**, or **Low**, plus an overall summary review.

## How to reproduce it

1. Open the pull request in this repository.
2. In the right sidebar, under **Reviewers**, find **Copilot** and click **Request**.
3. Wait — a review typically completes in **under 30 seconds**.
4. Scroll down and read through Copilot's comments. Where possible, Copilot attaches suggested changes that can be applied in a couple of clicks.

## Good to know

- By default Copilot leaves a **Comment** review, not an "Approve" or "Request changes" review, so its feedback does not count toward required approvals on a pull request.
- Copilot's review comments behave like human review comments: you can react to them, reply to them, and resolve them.
- Reviews can be automated for every PR, and custom review instructions can be added with `.github/copilot-instructions.md`.

See the official documentation: [Using GitHub Copilot code review](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/request-a-code-review/use-code-review).
