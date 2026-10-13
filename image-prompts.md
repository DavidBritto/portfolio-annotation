# AI Image Generation Prompts for Portfolio Project Previews

Use these prompts in **Midjourney v6**, **Flux.1**, **DALL-E 3**, or **Google Imagen** to generate high-resolution UI preview screenshots for each project card.

Recommended target specifications:
- **Aspect Ratio**: `16:9` or `16:10` (`--ar 16:9` in Midjourney)
- **Destination folder**: Save the images in `assets/` as:
  - `assets/specly.png`
  - `assets/devops.png`
  - `assets/onaxale.png`
  - `assets/kuarahy.png`

---

## 1. Specly — Spec-Driven Agentic AI CLI
> **Goal**: A high-density, ultra-clean developer terminal showing structured AI agent scaffolding and spec enforcement.

```text
A high-resolution, ultra-crisp UI screenshot of a modern developer terminal in dark mode, floating on an obsidian black surface with subtle blueprint grid lines. Inside the terminal window, clean monospace code and CLI output from 'npx specly apply' is displayed with syntax highlighting. Visible colored status badges: emerald green '[SPEC_VERIFIED]', amber '[CONTRACT: VALID]', and cyan '[AI_AGENT: DETERMINISTIC_EXECUTION]'. Sleek macOS-style terminal top bar with subtle red, yellow, and green window dots. High-end developer tooling aesthetic, styled like Vercel, Linear, and Raycast, zero clutter, 8k resolution, photorealistic UI capture. --ar 16:9
```

---

## 2. DevOps Engineering Lab — Cloud Infrastructure & CI/CD
> **Goal**: An enterprise cloud architecture & automated deployment pipeline dashboard.

```text
A sleek, modern cloud infrastructure observability and CI/CD pipeline dashboard in dark obsidian mode. The interface features a glowing node-based deployment graph connecting GitHub Actions workflows to Terraform IaC provisioning and Kubernetes cluster pods. Clean metrics widgets displaying CPU telemetry, 99.99% uptime badges, and AWS resource topology (VPC, ECS, CloudWatch). Color palette of deep slate black (#0c0e14) with electric cyan, amber, and mint green glowing connection lines. Hyper-detailed UI design, crisp typography, clean vector aesthetic, 8k resolution. --ar 16:9
```

---

## 3. Onaxale — Serverless E-Commerce Architecture
> **Goal**: A luxury, minimalist dark-mode e-commerce storefront with subtle cloud telemetry overlays.

```text
A premium, dark-mode luxury e-commerce web storefront mockup for an organic skincare brand named Onaxale. Sleek minimalist layout showing aesthetic cosmetic bottles (vitamin serums, nourishing facial creams) on an elegant dark marble background with soft studio lighting. Modern shopping cart drawer open on the right displaying Mercado Pago serverless checkout and an ultra-fast edge CDN delivery badge ('<80ms TTFB'). Deep black and gold aesthetic, ultra-clean Swiss typography, responsive desktop view, photorealistic web design showcase. --ar 16:9
```

---

## 4. Kuarahy — Real-Time Solar Telemetry Platform
> **Goal**: A clean, futuristic environmental telemetry dashboard displaying solar radiation trajectories.

```text
A futuristic, dark-mode solar telemetry and renewable energy web application dashboard. The central visual is a glowing golden-amber arc depicting real-time sun elevation and astronomical irradiation curves against a coordinate grid. Surrounding modular widgets display live solar irradiance (W/m²), UV index, and weather forecasts from Open-Meteo with sleek charts and clean data dials. Dark charcoal background (#08090c) with warm amber and solar gold data visualizations, minimalist Next.js 15 aesthetic, sharp typography, 8k resolution. --ar 16:9
```

---

## How to Integrate in `index.html`

Once you have generated and saved the 4 images into `assets/`, update each project card's background in `index.html`:

```css
.project-card.specly {
  background: linear-gradient(180deg, rgba(15, 17, 23, 0.82) 0%, rgba(15, 17, 23, 0.96) 100%),
              url('assets/specly.png') center / cover no-repeat;
}

.project-card.devops {
  background: linear-gradient(180deg, rgba(15, 17, 23, 0.82) 0%, rgba(15, 17, 23, 0.96) 100%),
              url('assets/devops.png') center / cover no-repeat;
}

.project-card.onaxale {
  background: linear-gradient(180deg, rgba(15, 17, 23, 0.82) 0%, rgba(15, 17, 23, 0.96) 100%),
              url('assets/onaxale.png') center / cover no-repeat;
}

.project-card.kuarahy {
  background: linear-gradient(180deg, rgba(15, 17, 23, 0.82) 0%, rgba(15, 17, 23, 0.96) 100%),
              url('assets/kuarahy.png') center / cover no-repeat;
}
```
The gradient overlay (scrim) guarantees that your project titles, descriptions, and tags remain 100% legible with strict WCAG contrast while giving the card rich visual depth.
