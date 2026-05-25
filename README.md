<div align="center">
  <h2>Kaustubha Eluri</h2>
  <p><strong>Agentic AI & Software Engineer</strong> · M.S. Computer Science, Northeastern University (Silicon Valley) · U.S. Citizen</p>
  <a href="https://linkedin.com/in/kaustubha-ve"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
  &nbsp;
  <a href="mailto:kaustubha.ev@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=Kaustubha-09&label=Profile+views&color=0e75b6&style=flat-square"/>
</div>

---

I build AI-powered systems that work for everyone — including the 2.2 billion people with visual impairments that most engineers never design for. My background is unusual: I started as an architectural engineer, transitioned into CS, and that cross-domain perspective shapes how I approach system design. My work spans agentic AI, accessibility-first mobile and web platforms, and ML systems that go from research to production.

[Featured on Northeastern Silicon Valley](https://siliconvalley.northeastern.edu/kaustubha-eluri-aspiring-product-manager/)

---

## Awards

- **Laurel & Scroll 100 Award**, Northeastern University *(Apr. 2026)* — Selected among top graduating students for academic achievement, leadership, and impact. [[Inductees]](https://distinction.northeastern.edu/laurel-and-scroll-100/laurel-and-scroll-100-inductees-2026/) [[NU News]](https://news.northeastern.edu/2026/04/15/laurel-and-scroll-100-2026-inductees/)
- **Silicon Valley Leadership Legacy Award**, Northeastern University *(Apr. 2026)* — Recognized for leadership and contributions to the Northeastern Silicon Valley community.
- **Khoury College Recognition (Nominee)**, Northeastern University *(2026)* — Nominated for academic excellence and contributions to Khoury College of Computer Sciences.
- **Top Project Recognition** *(2025)* — Awarded for *RapidTriage AI* for technical depth and evaluation rigor.
- **Hackathon Recognition – Student Networking Innovation** *(2024)* — Won for *Husky Mingle*, a mobile-first campus collaboration platform.

---

## Experience

**Lead Software Engineer (AI/ML & Accessibility) — Smith-Kettlewell Eye Research Institute** *(San Francisco, CA | Jul–Jan 2026)*
[Featured in Khoury College News](https://www.khoury.northeastern.edu/with-this-ai-driven-tool-blind-users-can-experience-youtube-and-tiktok-videos-too/) · Led end-to-end engineering for [YouDescribeX](https://ydx.youdescribe.org/home), an AI-assisted audio description platform for blind & low-vision users. Shipped bi-weekly releases to 40+ users at <1% crash rate. Built Infobot (86% top-3 hit rate on 300-question benchmark), improved performance 15%, retention 20%, reduced task time 28% via usability studies, and achieved WCAG AA+ compliance. Promoted from Research Assistant.

**Lead AI Engineer, Data & Compliance — Evenness, Inc.** *(Atlanta, GA | May–Feb 2026)*
Built RAG-backed agentic workflows covering 100% of WCAG 2.1 + multi-standard (EEA, ADA, AODA). Cut analysis runtime 60–70%, reduced audit cycle time 15→9 min, saved ~120 hrs/quarter. Maintained 99.9% uptime and p95 latency <300ms across 4 production microservices. Promoted from Agentic AI Engineer Intern.

**Teaching Assistant — CS 5520 Mobile Application Development, Northeastern University** *(San Jose, CA | Sep 2024–Aug 2025)*
Mentored 30+ graduate students on Android (Java, MVVM, Firebase). Built Python auto-graders that cut grading time 40%. Redesigned 2 major assignments with faculty, raising completion rates 12 pts. 90% of students shipped fully functional final projects.

**Technical Product Development Intern — Folio.Works** *(New York, NY | Dec 2023–Jul 2024)*
Shipped 6 production releases for a Flutter-based iOS/Android app (200+ fellows). Improved startup time ~400ms, cut crash rate 35%, drove 65% MAU adoption within 30 days of each release. Built 60+ test cases, growing regression coverage to 80%.

**Graduate BIM Engineer — bimgrafX** *(Phoenix, AZ | Nov 2020–Mar 2022)*
Delivered 12+ Building Information Models using Revit, coordinating multidisciplinary inputs at 99% design accuracy. Promoted from intern to full-time within 12 months.

---

## Projects

**[RapidTriage](https://github.com/Kaustubha-09/RapidTriage)** — Emergency triage shouldn't require typing. Cross-platform medical app with voice input, GPS hospital discovery, and hybrid AI (LLM symptom parsing + MTS/ESI-inspired clinical rules). Assesses emergencies in ~3.7s. Safety-biased fallback to YELLOW (Urgent) on low classifier confidence — Type-II error is much worse than Type-I in triage. `React Native (Expo)` · `Go` · `Gemini / Claude / OpenAI multi-provider`

**[voya](https://github.com/Kaustubha-09/voya)** — Native SwiftUI iOS travel companion: explore stays, plan budgets, join travel squads, fork expert playbooks, earn rewards. 11 feature modules, 100 Swift files, ~14k LOC, **zero external dependencies**. Single `ViewState<T>` async-state shape across 13 ViewModels. Keychain-backed JWT + Face ID/Touch ID app-lock. `Swift 5.9` · `SwiftUI` · `Combine` · `iOS 17+`

**[Echolin.ai](https://github.com/Kaustubha-09/Echolin.ai)** — Deepfake detection is only useful if it's explainable. React 19 + Flask + PyTorch Vision Transformer pipeline classifies images & videos with optional LLM explanation; **`artifacts` field honestly called out as synthetic** because the base ViT is binary-only. Supabase auth with row-level security on every table. `React 19` · `Flask` · `PyTorch ViT` · `Supabase`

**[SemanticVideoUnderstanding](https://github.com/Kaustubha-09/SemanticVideoUnderstanding)** — Frame-by-frame video prompting is redundant. Designed a semantic-diff prompting framework for Vision-Language Models that describes only what *changed* between consecutive frames. **50–70% token reduction** vs. baseline on a 141-video action dataset, with tiktoken-accurate measurement and 18 no-network unit tests. `Python` · `GPT-4o` · `tiktoken`

**[HuskyMingle](https://github.com/Kaustubha-09/HuskyMingle)** — Campus social super-app for Northeastern: cross-platform Web (Next.js 15 + NestJS), native Android (Kotlin + Jetpack Compose), native iOS (SwiftUI + Keychain + Face ID), all against one backend. Verified `.edu` onboarding, threaded comments, Stories, marketplace, course catalog, smart matching. **Won campus hackathon track for student networking innovation.** `Next.js · NestJS · Kotlin Compose · SwiftUI`

**[patient-intake-agent](https://github.com/Kaustubha-09/patient-intake-agent)** — Terminal AI agent for patient intake & scheduling: GPT-4o drives the conversation, deterministic Python tools own every data-bearing operation (Google Maps Geocoding, urgency-policy provider ranking). **Two-layer emergency gate** (system-prompt directive + tool-layer refusal) so the 911 escalation is unbypassable. `--demo` mode shares the production tool layer. `Python 3.12` · `GPT-4o` · `Google Maps Geocoding`

**[utility-ai-assistant](https://github.com/Kaustubha-09/utility-ai-assistant)** — Four production-grade LLM-app patterns in one small codebase: MCP-style tool calling, TF-IDF RAG over policy docs, keyword intent routing, and grounded Gemini 2.5 Flash synthesis with explicit `CONFIDENCE: HIGH/MEDIUM/LOW` labels. Vendor swap from Anthropic → Gemini was a one-file diff. FastAPI REST + Streamlit chat share one router/tools/RAG/LLM core. `FastAPI` · `Streamlit` · `Gemini 2.5 Flash` · `scikit-learn`

**[AIChatAssistant](https://github.com/Kaustubha-09/AIChatAssistant)** — Native Android chat client for OpenAI-compatible LLMs. **Streaming SSE via raw OkHttp** (Retrofit only for non-streaming because `Call.execute()` buffers and defeats `stream: true`). Manual `ServiceLocator` DI instead of Hilt; mock provider that streams the *same* `Resource<Loading/Success/Error>` pipeline as the real API. `Java 17` · `Material 3` · `Room` · `OkHttp SSE`

**[NEUQuest](https://github.com/Kaustubha-09/NEUQuest)** — Cross-platform campus events & budget-trip app for Northeastern: native Android (Java + Material 3) and native iOS (SwiftUI + MVVM) sharing one Firebase project and one Gemini 1.5 Flash model for AI-ranked event feeds and trip-name generation. Layered NEU-domain auth (client regex + Realtime DB security rule). `Android Java · SwiftUI · Firebase · Gemini`

**[Notification Urgency Classifier](https://github.com/Kaustubha-09/notification_classifier)** — NLP system to classify notifications into Eisenhower Matrix priority levels using TF-IDF + Multinomial Naive Bayes. Improved accuracy from 0.41 → 0.93 over a rule-based baseline. Added DistilBART summarization for condensed previews. `Python` · `scikit-learn` · `HuggingFace`

**[Spambase](https://github.com/Kaustubha-09/Spambase)** — Four-model spam-classification study: hand-rolled Manual Naive Bayes (log-space arithmetic + Laplace smoothing) vs. Bernoulli NB · Logistic Regression · SVM on the 4,601-row Spambase dataset. Logistic Regression won on AUC-ROC (0.97); auto-generated confusion / ROC / top-spam-word plots. `Python` · `scikit-learn` · `NLTK`

---

## Research & Leadership

**[NEURAI Research Lab](https://neurai.sites.northeastern.edu/our-team/kaustubha-eluri/) — Founding Researcher** *(Mar–Dec 2025)*
Interpretable and responsible ML research. Co-authored a proposal that secured $2k in compute credits. Built baseline pipelines adopted by new lab members.

**APMC (Aspiring Product Managers Club) — President** *(Jan 2024–Dec 2025)*
Led student org for PM interview prep, case practice, and mentoring. Received student leadership award 2025.

**AI/Data Club — Core Organizer** | **Adobe Creative Campus Club — VP** | **Northeastern Student Ambassador**

---

## Certifications

- **Data Science for Construction, Architecture and Engineering** — edX *(Dec. 2024)*
- **Generative AI for Creativity and Innovation** — Adobe *(Nov. 2023)*
- **Foundations of Cloud Computing** — Codecademy *(Feb. 2023)*
- **Programming Essentials in Python (PCAP)** — Cisco *(Aug. 2022)*
- **Introduction to Artificial Intelligence** — University of Helsinki *(Jul. 2022)*
- **BIM: From Sketch to Digital Twin** — Coursera *(Mar. 2022)*
- **Computer Applications of AI and e-Construction** — edX *(Apr. 2022)*

---

## Stack

`Python` `Java` `JavaScript` `TypeScript` `HTML` `CSS` `Swift` `Dart` · `React` `React Native` `Flutter` `FastAPI` `Node.js` · `PyTorch` `TensorFlow` `HuggingFace` `LangChain` `OpenAI` `scikit-learn` `NumPy` `Pandas` · `PostgreSQL` `MongoDB` `Firebase` `SQLite` `Pinecone` `ChromaDB` · `Docker` `GitHub Actions` `Git` `AWS` `GCP` · `Revit` · `WCAG AA+` `NVDA/VoiceOver`

---

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Kaustubha-09&theme=react-dark&hide_border=true&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FFFFFF&days=7" alt="GitHub Activity Graph"/>
</div>
