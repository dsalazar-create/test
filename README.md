# test
test360
Sales Leader 360° Feedback & Coaching Portal

The Sales Leader 360° Feedback Portal is a production-ready, highly interactive, single-file application designed to capture raw, honest, and anonymous performance feedback for sales managers.

It evaluates managers on the critical behaviors that keep sales representatives executing at quota: Coaching Frequency & Impact, Team Meeting Quality, Functional Sales Expertise, and High-Stakes Availability. It also features a passcode-protected administrative dashboard for HR, directors, and executives to aggregate ratings and safely analyze constructive feedback.

🚀 Live Demo & Deployment Quick-Start

Because the application is built as a highly portable, self-contained index.html file, you can deploy it company-wide in less than 60 seconds.

Deploying to GitHub Pages (Free Hosting)

Create a new public repository on your GitHub account.

Create a new file inside the repository named index.html.

Copy the entire HTML code from the Canvas editor and paste it into the index.html file, then commit.

Navigate to your repository's Settings > Pages.

Under "Build and deployment", set the Source to Deploy from a branch, select your main branch, and click Save.

GitHub will generate a secure (https://) live link for your team within a few seconds!

🔑 Security & Administration

To protect feedback objectivity and foster absolute honesty among team members, the analytics panel is secured behind a passcode modal.

Default Admin Passcode: admin360

Session Safeguard: The dashboard includes a "Lock Dashboard" action button. This immediately terminates the authenticated state and returns the interface to the agent submission funnel, preventing unauthorized viewing on unattended workstations.

🌟 Key Features

1. 100% Anonymous Agent Submission Funnel

Multi-Step Wizard: Gently guides agents through the review process to prevent evaluation fatigue.

Aggregated Submissions: Submissions are randomized inside the dashboard, stripped of individual submission metadata (like timestamps or browser signatures), keeping individual identities untraceability-safe.

Constructive Prompts: Guides feedback utilizing the Start, Stop, and Continue feedback framework.

2. Live Management & Director Dashboard

Overall Health Score: Instant calculation of a manager's composite score (out of 5.0).

Trait-Specific Metrics: Breaks scores down to pinpoint exactly where a leader excels or needs guidance.

Frequency Distributions: Visual distribution metrics representing how often huddles and coaching sessions are actually occurring versus how often leaders think they are.

Custom Charting: Interactive responsive progress indicators built with lightweight, dynamic inline SVG components.

3. Dynamic Interactive State

Adding new managers or submitting a new anonymous evaluation instantly updates and recalculates the dashboard averages and qualitative card blocks in real-time.

🛠️ Technical Implementation & Architecture

This application uses a serverless, client-side React runtime architecture:

Framework: React 18 (Production Build via CDN)

Styling: Tailwind CSS Engine (Fully responsive layouts matching standard light/dark viewport parameters)

Icons: Built-in SVG System Icon Engine (Replaces heavy vector packages like FontAwesome or external Lucide-React CDNs, allowing zero-latency loading and reliable offline functionality)

Compiler: Babel Standalone (Compiles JSX directly in the browser dynamically)

📊 Core Rating Metrics

The portal measures four critical leadership areas:

Metric

Focus Area

Impact

Coaching Impact

1-on-1 strategic growth and pipeline reviews.

Determines quota readiness and onboarding speed.

Meeting Value

Structured huddles, team priorities alignment.

Prevents pipeline bottlenecks and increases alignment.

Leader Expertise

Functional sales knowledge, deal execution.

Boosts representative confidence during complex negotiations.

Availability

High-stakes availability and approval turn-times.

Prevents deal slippage and keeps high-priority targets moving.

🤝 The Sales Leader Pledge

"True leadership growth comes from hearing the objective, sometimes difficult, truth."

This system serves as a bridge between frontline sales representatives and management, aligning executive strategies with ground-level coaching realities.
