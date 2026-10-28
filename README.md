# 🛰️ eXecuteAI

**eXecuteAI** is an enterprise-grade agentic AI observability framework engineered to detect, isolate, and automatically resolve silent user interface failures, runtime console exceptions, and structural layout anomalies across modern web infrastructure.

---

## 📌 Project Overview & Context
* **Founder:** Emmanuel Fadipe (Undergraduate Mechatronics Engineering student)
* **Development Track:** From Hackatons to a startup.
* **Platform Architecture:** Developed via mobile-optimized browser environments on GitHub Codespaces, purposefully architected for deployment onto dedicated local physical hardware.

---

## 💡 The Core Problem
Unlike compiled backend programming languages that throw fatal exceptions when processes break, web-facing client-side architectures (HTML, CSS, and browser-executed JavaScript) regularly fail **silently**. If a script fails to execute, a mobile viewport suffers from rigid layout overflows, or an internal event handler encounters an unhandled state, the browser often bypasses the breaking line and continues rendering.

These silent failures lock critical user interface components—such as payment gateways, authentication flows, and security verifications—into unresponsive states. Organizations lose substantial revenue because these failures are completely invisible to standard server-side monitors until users abandon the application entirely.

---

## 🚀 Architectural Solution: Agentic AI Observability
eXecuteAI implements an automated, end-to-end frontend diagnostic, optimization, and self-correcting platform running across four distinct asynchronous layers:

1. **Automated Web Verification Engine:** The system initializes isolated headless browser instances (via Puppeteer/Playwright) to emulate organic, production-grade user validation tracks and navigate target interfaces.
2. **Runtime Console Interception:** The diagnostic agent attaches directly to runtime console logs and stack traces, capturing background JavaScript exceptions, unhandled race conditions, and network payload irregularities securely and dynamically.
3. **Context-Optimized Multi-Model Routing:** Captured error payloads are systematically trimmed to include relevant code snippets surrounding the failure line, preserving tight token windows. Payloads are routed dynamically based on complexity:
   * *Structural Layout & CSS Variances:* **Gemini 1.5 Flash** (High-efficiency processing).
   * *Standard Interactive Elements & Form Validation:* **OpenAI GPT-4o** (Balanced performance execution).
   * *Complex Async Exceptions & Execution Loops:* **Claude 3.5 Sonnet** (Advanced reasoning processing).
4. **Isolated Sandbox Verification Layer:** Proposed modifications are executed offline inside a secure, non-networked, read-only container shell with strict 30-second timeouts. This process mitigates security risks, maintains infrastructure integrity, and ensures verification before reporting back to developers.

---

## 🎨 User Interface Design & Dashboard Telemetry
To ensure clear technical visibility, the core platform layout provides an intuitive visualization layer across its operational endpoints.

* **Integrated Editor Workspace:** Embedded directly into the management panel is a dedicated code telemetry panel matching standard editor coloration systems (`#1E1E1E`).
* **Visual Diff Engine:** Code changes are mapped inside this environment using distinct monospaced formatting. Broken or omitted lines are highlighted in clear warning variants, while agentic AI corrections are designated in high-contrast success tones—optimizing review speeds for technical managers.

---

## 📂 Repository Architecture

This application is deployed across an optimized multi-repository infrastructure to cleanly isolate public client interfaces from secure core evaluation routines:

* **`execute-app-frontend` (This Repository):** Public-facing client-side environment providing the UI canvas, global styling layouts, dashboard interfaces, and API gateway routing scripts.
* **`execute-core-engine` (Private Backend):** Secure backend service layer hosting isolated database transactions (Supabase RLS), sandbox execution routines, custom automation crons, and multi-model AI routing mechanisms.

---

## 📊 Subscription Options & Resource Quotas
Platform plans scale progressively around execution capacity and monitoring depth to balance underlying resource utilization cleanly.

* **Developer Sandbox (\$0/mo):** Includes 2 manual scans per month. Powered by Gemini 1.5 Flash processing. Configured with a 50KB maximum DOM parsing ceiling.
* **On-Demand Scan Tier (\$1.50/scan):** Individual, high-priority diagnostic tracking. Unlocks multi-model routing capabilities and single-use sandbox evaluations.
* **Professional Tier (\$19/mo):** Includes 50 manual scans per month. Grants access to persistent dashboard workspaces, automated webhook registrations, and a flexible account-pause mechanism that temporarily pauses automated active tracking while preserving configuration data.
* **Business Tier (\$59/mo):** Includes 500 automated scans per month. Deploys background scheduling loops for recurring monitoring. Features instant notification alerts integrated via webhook engines like Slack and Discord.
* **Enterprise Tier (\$149/mo):** Includes 1,500 automated background scans per month across up to 50 custom domains managed from a single tenant portal. Enables custom, white-label downloadable technical reports.

---

## 🛡️ Reliability Frameworks & Operational Safeguards

### 1. Automated Self-Correction Loop
If an optimization patch fails to resolve the recorded log within the isolated sandbox verification layer, the system catches the exception, logs the parameters, and cycles the execution payload through advanced LLM reasoning paths for up to 3 automated remediation cycles. If the state cannot be programmatically resolved, the interface switches to the **Non-Invasive Architectural Advice Engine**, outputting high-level contextual breakdowns and optimization documentation to guide the manual developer response.

### 2. External Content Delivery Network Interception
When tracked frontend exceptions trace directly to third-party public assets (such as faulty scripts or dependencies sourced from external asset networks), the core pipeline bypasses local patch-generation completely. The dashboard outputs explicit dependency vulnerability notices instead, reducing investigation latency while maintaining complete internal system stability.

### 3. Account Transparency Notification Engine
To maintain clean user billing visibility, automated background cron routines track account activity metrics. The notification infrastructure distributes regular statements documenting account metrics, credit allocations, and usage history to ensure operational predictability.

### 4. Expansion & Infrastructure Scaling Strategy
* **Phase 1 (Current):** System design, prototyping, and local physical track hardware testing.
* **Phase 2 (Deployment):** Distribution via international billing frameworks, including Paystack, to secure cross-border payment flexibility and regional processing compatibility.
* **Phase 3 (Scale):** Upon establishing predictable platform recurring revenues, corporate restructuring via Stripe Atlas to establish a centralized legal framework, incorporating advanced checkout payment rails and redundant global transaction routing.
*