# Architecture Plan: Modern Engineering Hub (Option B)

## 1. Vision & Architectural Purpose
Build a fast, minimalist, and deeply professional **Engineering Hub & Portfolio** for David Britto. 
Positioned as a senior technical artifact communicating authority in:
- **Linux Systems Engineering**
- **AWS Cloud Architecture**
- **Spec-Driven Agentic AI Tooling**

It abandons toy OS simulations in favor of an **Editorial & Terminal-Infused Engineering Portfolio**—combining clean ASCII art, a functional terminal/interactive code hero, deep case study breakdowns, and a scalable technical writing/blog foundation.

---

## 2. Visual Identity & Design System
- **Theme**: Deep Monochromatic Obsidian (`#08090c` background, `#0f1117` elevated panels, `#161922` subtle borders).
- **Accents**:
  - AWS Amber / Terminal Glow: `#f59e0b` / `#fbbf24`
  - Cloud / Systems Cyan: `#38bdf8`
  - Success Green: `#10b981`
  - Pure white headings (`#f9fafb`) and legible body copy (`#9ca3af`).
- **Typography**:
  - Monospace (Code, Telemetry, ASCII): `JetBrains Mono`, `Fira Code`.
  - Body & Titles: `Inter` / `Geist` for crisp readability.
- **Graphic Elements**:
  - Tasteful ASCII Art hero header (terminal branding).
  - AWS Builder Center style syntax headline with typewriter effect.
  - Clean architectural topology cards and code snippets.

---

## 3. Page Structure & Component Hierarchy

1. **Terminal ASCII Header & Nav**:
   - Minimalist ASCII banner (`DAVID BRITTO // SYSTEMS · CLOUD · AGENTIC AI`).
   - Clean top navigation: `[Projects]` `[Case Studies]` `[Writing]` `[Resume/ATS]` `[Contact]`.

2. **Hero: AWS Builder Style Interactive Code Headline**:
   - Code syntax highlighted dynamic typewriter:
     `if building: start_here()`
     `if architecting: aws_cloud()`
     `if scaling: linux_systems()`
     `if automating: agentic_ai()`
     `if shipping: devops_pipelines()`
   - Senior profile statement and live availability badge.

3. **Engineering Showcase (The 4 Flagship Projects)**:
   - High-density, structured technical cards:
     - **Specly**: Spec-Driven Development CLI (npm package, Agentic AI, TypeScript).
     - **DevOps Lab**: #90DaysOfDevOps (Terraform, Kubernetes, Docker, CI/CD).
     - **Onaxale**: Serverless E-Commerce Migration (>90% AWS cost reduction).
     - **Kuarahy**: Real-time solar telemetry and energy computation.
   - Architecture highlights, metrics, and direct evidence links (GitHub, npm, Live).

4. **Deep Dive: Zero to Cloud Production Case Study**:
   - Step-by-step architectural breakdown of Onaxale (S3/CloudFront -> Lambda API -> DynamoDB).
   - Clear technical decision log (cost vs. latency vs. operational overhead).

5. **Technical Writing / Blog Section (Scalable Foundation)**:
   - Chronological list of engineering articles, architectures, and lessons learned.
   - Filterable by tags: `AWS`, `Linux`, `Agentic AI`, `DevOps`.

6. **Interactive Utility Drawer & ATS Resume**:
   - 1-click ATS Markdown resume copy.
   - Direct contact channels (Email, LinkedIn, GitHub).

---

## 4. Technical Implementation Principles
- **Clean Vanilla Architecture**: Native HTML5, modern CSS custom properties, and lightweight vanilla ES6.
- **Zero Build Friction**: Direct deployment to GitHub Pages on every `git push`.
- **Performance**: Sub-100ms load, zero layout shift (CLS 0), 100/100 Lighthouse score.
