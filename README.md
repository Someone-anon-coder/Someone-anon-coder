# 👋 Hi, I'm Aayush Choudhary — @Someone-anon-coder

### 🧪 SDET / QA Automation · 💻 Backend & Systems · 🔐 Cybersecurity

I build **test infrastructure and the tooling around it** — frameworks, self-healing locators, CI pipelines — and I break things on purpose in my security practice. Most of my work starts from a real failure mode (a selector that dies on a redesign, a container that shouldn't be escapable, a regression suite that takes too long to be useful) and ends with something measured, not something claimed.

I'm an implementation-oriented engineer: B.E. in Automation & Robotics with an Honours specialization in **Cybersecurity**, ten months as an SDET building a production Playwright framework from scratch, and a published npm package to show for the TypeScript side.

**Open to SDET / QA Automation / SDE / Application Security roles** — Pune, Bengaluru, Hyderabad, or remote.

📫 [aayush.off@gmail.com](mailto:aayush.off@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/aayush-choudhary-a52aab25b/) · ✍️ [Medium](https://medium.com/@computer-info-1) · 🌐 [breechlab.com](https://breechlab.com)

---

### 🛠️ Tech Stack

* **Testing & QA:** Playwright, Pytest (xdist), Selenium WebDriver, K6, Postman, BrowserStack, Page Object Model, risk-based regression design.
* **Languages:** Python, TypeScript/JavaScript, Java, C++, C, Go, SQL.
* **Backend & Infra:** SQLAlchemy (async, multi-engine), PostgreSQL, MySQL, MongoDB, Docker, Jenkins, GitHub Actions, Spring Boot (in progress).
* **Security:** Linux privilege escalation, SUID/capability abuse, container escape, mTLS, OpenSSL, SHA-256, Nmap, OSINT tradecraft.
* **AI & ML:** Google Gemini API, Reinforcement Learning (DQN, SAC), OpenCV, YOLO, Scikit-learn, Pandas.
* **Robotics & Sim:** ROS concepts, MAVSDK, PyBullet, Gazebo, Protobuf.

---

### 💼 Experience

**QA Automation Engineer (SDET) — Bynry Services · Sep 2025 – Jun 2026**

* Built **Forseti** from scratch — an async Playwright + Pytest framework with **163 Page Object Models** and **4,200+ automated tests**, sustained at a **>90% pass rate**.
* Cut regression cycle time **30–50%** through `pytest-xdist` parallelization and risk-based test tagging.
* Wrote an **async SQLAlchemy multi-engine router** validating data across **13 microservice databases**.
* Containerized the suite and wired it into a **Dockerized Jenkins CI/CD** pipeline; built an AI-assisted flakiness analyzer on top of run history.
* **Heimdall** — async-first CRM automation framework (Playwright + MongoDB) with a K6 load-testing suite validated at **50,000 concurrent virtual users**.
* Logged, triaged, and verified **150+ defects**; held code-review and merge authority, reviewed interns' PRs, and onboarded one intern to independent test authorship.

> Forseti and Heimdall are proprietary to Bynry, so there are no public repos for them. Everything below is public and inspectable.

---

### 🔭 Featured Projects

#### 🧪 Testing & QA Automation
| Project | Description | Tech |
| :--- | :--- | :--- |
| **[playwright-eir](https://github.com/Someone-anon-coder/Eir)** · [npm](https://www.npmjs.com/package/playwright-eir) | Self-healing locator engine for Playwright, published at **v1.0.0**. Fingerprints elements while the suite is green, then matches a broken selector against that fingerprint with six deterministic scorers. **0.0% false-heal rate in every class of an 8-class seeded mutation benchmark** — and the misses are published too. Drop-in: change one import. | TypeScript (strict), Zod, pnpm monorepo |
| **[FinacPlus QA](https://github.com/Someone-anon-coder/FinacPlus_QA)** | Two independent Playwright suites — a UI journey through DemoQA Book Store and an API lifecycle against reqres.in — including an explicitly documented test that asserts a `404` because the mock is stateless, rather than skipping the check. | JavaScript, Playwright, CI |
| **[Bynry QA Assessment](https://github.com/Someone-anon-coder/bynry-qa-automation-assessment)** | Take-home QA automation assessment. Companion: [inventory management assessment](https://github.com/Someone-anon-coder/bynry-inventory-management-assessment). | Python, Playwright |

📖 Build story: [Building playwright-eir — a self-healing locator engine with a measured 0% false-heal rate](https://computer-info-1.medium.com/building-playwright-eir-a-self-healing-locator-engine-with-a-measured-0-false-heal-rate-70eac1c27bf7)

#### 🔐 Cybersecurity
| Project | Description | Tech |
| :--- | :--- | :--- |
| **[BreechLab](https://github.com/Someone-anon-coder/BreechLab)** | Solve logs from a five-track offensive-security CTF platform — **63 of 75 levels solved**, three tracks complete with certificates. Each level directory carries a `notes.txt` with goal, recon, exploit chain, and flag. | Linux, privesc, container escape, OSINT |
| **[SeedPass](https://github.com/Someone-anon-coder/Password_Generator)** | Deterministic, seed-based password generator CLI — same inputs always regenerate the same high-entropy credential, so nothing has to be stored. | C++, SHA-256 |
| **[Spyware Research](https://github.com/Someone-anon-coder/Spyware)** | *Educational research tool* for understanding system monitoring (key/mouse logging) and data-capture techniques. | Python, JSONL |

**BreechLab track progress**

| Track | Focus | Solved |
| :--- | :--- | :--- |
| Phantom | Chained SSH credential discovery, restricted-shell escape, local port forwarding | 16 / 16 ✅ |
| Ghost | Privilege escalation, SUID abuse, applied crypto | 23 / 23 ✅ 📜 |
| Ghost II | Linux capabilities, deploy pipelines, signer/policy abuse — own flag per level | 18 / 18 ✅ 📜 |
| Phantom II | Container escape — Docker socket, privileged host-PID via `/proc/1/root` | 3 / 4 🔄 |
| Spectre | Professional OSINT tradecraft, counter-intel, Berkeley Protocol reporting | 3 / 14 🔄 |

📜 = completion certificate committed to the repo.

#### 🧠 Software Engineering & Generative AI
| Project | Description | Tech |
| :--- | :--- | :--- |
| **[Arbiter](https://github.com/Someone-anon-coder/Arbiter)** | Java from fundamentals to a deployed **microservices test-management platform**, built in public. Every line is written by me — the AI acts as instructor and evaluator only, never implementer. | Java, Spring Boot, Docker |
| **[Live-Translator](https://github.com/Someone-anon-coder/Live-Translator)** | Local-first real-time screen translation for Linux with **sub-100ms** latency. Spatial clustering groups words into semantic blocks before translating; nothing leaves the machine. | Python, PyQt6, Tesseract OCR, multithreading |
| **[UIDAI Drishti Dashboard](https://github.com/Someone-anon-coder/UIDAI_Drishti_Analytics_Dashboard)** | AI-powered analytics platform for Aadhaar enrollment and demographic data, with a **conversational AI analyst** and dynamic plotting. | Streamlit, Gemini API, Plotly |
| **[AI Ecosystem](https://github.com/Someone-anon-coder/AI_Ecosystem)** | Hierarchical NLP framework that decomposes natural-language commands into executable PC tasks. | C++, Python, NLP |
| **[Echoes (Aura)](https://github.com/Someone-anon-coder/echoes-ai-friend)** | Google Cloud Gen AI Hackathon submission — a confidential wellness companion that calls Gemini on the user's behalf without ever exposing their keys. | React, TypeScript, Firebase, Gemini API |

#### 🤖 Robotics & Autonomous Systems
| Project | Description | Tech |
| :--- | :--- | :--- |
| **[AetherLink](https://github.com/Someone-anon-coder/AetherLink)** | Secure UAV telemetry channel using **mTLS** and **Protobuf** — a C++ onboard agent streaming to a Go ground-station backend. | C++, Go, MAVSDK, OpenSSL |
| **[Drone Operations](https://github.com/Someone-anon-coder/Drone-Operations)** | Suite for synthetic data generation, **YOLO-based collision avoidance**, and automated payload delivery. | Python, YOLO, OpenCV |
| **[Robotic Arm RL](https://github.com/Someone-anon-coder/Robotic_Arm)** | **EEG-controlled** 27-DOF robotic arm simulation using **Soft Actor-Critic (SAC)** to imitate human motion in PyBullet. | Python, PyBullet, RL |
| **[RL Drone Model](https://github.com/Someone-anon-coder/RL_Model)** | Autonomous drone navigation and speed control with hierarchical **Deep Q-Learning (DQN)**. | Python, Gazebo |

---

### 📈 Learning Journeys

I document what I learn as I learn it — each repo is a progression, not a dump.

* ☕ **[Java — Arbiter](https://github.com/Someone-anon-coder/Arbiter)**: fundamentals → data structures → Spring Boot → a real microservices platform.
* 🛡️ **[Cybersecurity](https://github.com/Someone-anon-coder/Cybersecurity)**: network scanning (Nmap) through cryptography and web app security.
* 🐍 **[Python](https://github.com/Someone-anon-coder/Python)**: decorators through sophisticated OOP patterns.
* 🐹 **[Golang](https://github.com/Someone-anon-coder/Golang)**: fundamentals through concurrency, networking, and web development.
* 👁️ **[OpenCV](https://github.com/Someone-anon-coder/OpenCV)**: computer vision and image manipulation.
* 📊 **[Matplotlib](https://github.com/Someone-anon-coder/Matplotlib)**: visualizing trends to understand data analysis.

### ✍️ Writing

I publish build notes and teaching articles on [Medium](https://medium.com/@computer-info-1) — including the Arbiter Java series, split into a practical [Guide track](https://computer-info-1.medium.com/list/arbiter-java-20daa21849c8) and a historically-grounded [Theory track](https://computer-info-1.medium.com/list/arbiter-java-theory-13ecf0e21149), plus parallel series on Cybersecurity, Python, Go, and Matplotlib.

### 💞️ Collaboration

I'm looking to collaborate on:

* **AI-native QA:** self-healing, resilient test automation for modern web apps.
* **Test infrastructure at scale:** parallelization, flakiness triage, and CI pipelines that teams actually trust.
* **Offensive security tooling:** container escape detection, privilege-escalation auditing, and OSINT automation.

### ⚡ Fun Fact

I once built a **Tic-Tac-Toe AI** that learned to win via Q-learning — and now I'm applying the same "learn the pattern, score the candidates" logic to teach test locators how to heal themselves when the UI shifts underneath them.
