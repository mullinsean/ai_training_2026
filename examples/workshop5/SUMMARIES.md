# Summaries: Recent Economics Papers on AI Adoption

*Generated 2026-06-15 from 7 papers in `example-files/`. Each entry covers metadata, focus, key findings, data sources, and methods & limitations.*

## Contents
1. [The Anthropic Economic Index report: Uneven geographic and enterprise AI adoption — Appel et al. (2025)](#1-the-anthropic-economic-index-report-uneven-geographic-and-enterprise-ai-adoption)
2. [The Rapid Adoption of Generative AI — Bick, Blandin & Deming (2024)](#2-the-rapid-adoption-of-generative-ai)
3. [Canaries in the Coal Mine? Six Facts about the Recent Employment Effects of AI — Brynjolfsson et al. (2025)](#3-canaries-in-the-coal-mine-six-facts-about-the-recent-employment-effects-of-artificial-intelligence)
4. [How People Use ChatGPT — Chatterji et al. (2025)](#4-how-people-use-chatgpt)
5. [Shifting Work Patterns with Generative AI — Dillon et al. (2025)](#5-shifting-work-patterns-with-generative-ai)
6. [Which Economic Tasks are Performed with AI? — Handa et al. (2025)](#6-which-economic-tasks-are-performed-with-ai-evidence-from-millions-of-claude-conversations)
7. [The Labor Market Effects of Generative Artificial Intelligence — Hartley et al. (2024)](#7-the-labor-market-effects-of-generative-artificial-intelligence)

---

## 1. The Anthropic Economic Index report: Uneven geographic and enterprise AI adoption

**Metadata** — Authors: Ruth Appel, Peter McCrory, Alex Tamkin, Miles McCain, Tyler Neylon, Michael Stern · Year: 2025 · Institution: Anthropic Economic Index Report · Pages: 47 · File: `Appel et al. - The Anthropic Economic Index report Uneven geographic and enterprise AI adoption.pdf`

**Focus** — This report studies the geographic and enterprise-level patterns of AI adoption using real usage data from Claude.ai and Anthropic's first-party (1P) API customers. It offers the first empirical examination of how frontier AI use is distributed across countries, U.S. states, and business sectors—drawing parallels to the historically uneven diffusion of earlier transformative technologies and raising concerns about whether AI's productivity benefits will concentrate in already-wealthy regions, potentially deepening global economic inequality.

**Key findings**
- AI adoption is heavily geographically concentrated and tracks income: Israel leads per-capita Claude usage at an Anthropic AI Usage Index (AUI) of 7.0× its population share, Singapore at 4.57×, and Australia at 4.10×, while low-income countries such as India (0.27×) and Nigeria (0.2×) show far below-expected usage; a 1% increase in GDP per capita is associated with a 0.7% increase in Claude usage per capita.
- Usage patterns diversify with adoption maturity: lower-adoption countries concentrate overwhelmingly on coding (over half of usage in India vs. roughly a third globally), while higher-adoption regions show broader use across education, science, and business operations.
- The share of "directive" (fully automated) Claude.ai conversations jumped from 27% in late 2024 to 39% by August 2025—the first period in which automation usage exceeded augmentation usage—and high-adoption countries tend toward more collaborative (augmentation) interaction even after controlling for task mix.
- Enterprise API customers use Claude in markedly more automated ways than individual consumers: 77% of 1P API transcripts show automation patterns versus roughly 50% for Claude.ai users, with coding dominating API use (~44% of API traffic maps to Computer and Mathematical tasks vs. 36% on Claude.ai).
- Model capability and economic value—not cost—drive enterprise task selection: higher-cost tasks are used more frequently, and a 10% cost reduction is estimated to increase usage by only ~3%; access to contextual information (long inputs) is a binding constraint, suggesting data modernization is a key bottleneck for broader enterprise adoption.

**Data sources**
- 1 million randomly sampled Claude.ai Free and Pro conversations from August 4–11, 2025 (geographic analysis)
- 1 million 1P API transcripts from August 2025 (~half of Anthropic's first-party API traffic; enterprise analysis)
- Previous Anthropic Economic Index conversation samples from Dec 2024/Jan 2025 (V1) and Feb/Mar 2025 (V2)
- U.S. Census Bureau Business Trends and Outlook Survey (BTOS) for firm-level AI adoption rates
- World Bank working-age population data; O*NET occupational task taxonomy; a bottom-up AI-generated taxonomy of user request clusters

**Methods & limitations** — Conversations are classified into economic tasks using the O*NET taxonomy plus a bottom-up clustering taxonomy, applied via privacy-preserving automated analysis (cells with <15 conversations or <5 accounts suppressed); geographic usage is normalized by working-age population to produce the AUI, with regression analyses relating AUI to income, task mix, collaboration mode, and cost. *Limitations:* geographic analysis relies on IP-address geolocation (excludes VPN/anycast traffic, uncertain for small regions); the API sample covers only ~half of 1P traffic, and each record is a prompt-response pair rather than a full session, which may affect collaboration-mode classification of multi-turn interactions.

---

## 2. The Rapid Adoption of Generative AI

**Metadata** — Authors: Alexander Bick, Adam Blandin & David J. Deming · Year: 2024 · Institution: NBER Working Paper No. 32966 · Pages: 34 · File: `Bick et al. - 2024 - The Rapid Adoption of Generative AI.pdf`

**Focus** — This paper measures the speed and intensity of generative AI (genAI) adoption in the United States using nationally representative survey data. The authors examine how many working-age Americans use genAI at work and home, how that adoption compares historically to the personal computer and the internet, which demographic and occupational groups lead adoption, how intensively users engage, and what time savings and potential productivity gains can be inferred—questions central to forecasting genAI's macroeconomic impact.

**Key findings**
- As of August–November 2024, ~39% of U.S. working-age adults (18–64) reported using genAI for work or personal use; 23% of employed respondents used it at least once in the prior week for work, and 9% used it every workday.
- Relative to each technology's first mass-market product launch, workplace genAI adoption has been as fast as the PC (~27% of workers in year two vs. 25% for PCs in year three), while overall (work + personal) genAI adoption has been faster than either PCs or the internet, likely due to lower adoption costs and ease of use.
- Adoption patterns by education, age, and occupation closely parallel early PC adoption—younger, more educated, higher-wage workers adopt first—with the main exception being gender: men lead in genAI adoption whereas women led early PC adoption due to clerical occupations.
- Between 1% and 5% of all U.S. work hours in the prior week involved direct genAI use; users report time savings equivalent to 5.4% of their work hours, implying 1.4% savings across all workers including non-users.
- A standard aggregate production model applied to the self-reported time-savings data yields an estimated potential aggregate labor productivity gain of ~1.1% at current adoption levels—consistent with, though slightly higher than, Acemoglu (2024)'s task-exposure estimate of 0.7%.

**Data sources**
- Real-Time Population Survey (RPS) — August and November 2024 waves (>10,000 respondents, benchmarked to the CPS)
- Survey of Working Arrangements and Attitudes (SWAA) — December 2024 wave (external validation)
- CPS Computer and Internet Use (CIU) supplement — historical PC/internet adoption comparisons

**Methods & limitations** — Original survey modules are fielded in two nationally representative online surveys (RPS, SWAA) with raking-based sample weights aligned to CPS benchmarks; adoption is compared across technologies by normalizing to time-since-launch, and potential productivity gains are estimated via a Cobb-Douglas production function calibrated with self-reported usage time and hours saved. *Limitations:* productivity estimates assume all reported time savings convert to output rather than on-the-job leisure (potentially overstating effects, given firm-level adoption lags individual use), and the survey relies on self-reported usage subject to measurement error or social-desirability bias.

---

## 3. Canaries in the Coal Mine? Six Facts about the Recent Employment Effects of Artificial Intelligence

**Metadata** — Authors: Erik Brynjolfsson, Bharat Chandar & Ruyu Chen · Year: 2025 · Institution: Stanford Digital Economy Lab (working paper) · Pages: 57 · File: `Brynjolfsson et al. - Canaries in the Coal Mine Six Facts about the Recent Employment Effects of Artificial Intelligence.pdf`

**Focus** — This paper examines whether the widespread adoption of generative AI since late 2022 has begun to reshape employment for workers in AI-exposed occupations. Using high-frequency administrative payroll data from ADP—the largest U.S. payroll processor—the authors track monthly employment and compensation by age group and occupational AI-exposure quintile from 2021 through July 2025, providing some of the first large-scale, near-real-time evidence on whether generative AI is displacing entry-level workers.

**Key findings**
- Early-career workers (ages 22–25) in the most AI-exposed occupations experienced a 13% relative decline in employment after widespread genAI adoption, even controlling for firm-level shocks; employment for older workers in the same occupations remained stable or grew.
- Workers aged 22–25 in the highest AI-exposure quintiles saw a 6% employment decline from late 2022 to July 2025, while workers aged 35–49 in the same quintiles saw employment grow by over 9%; young workers in less-exposed jobs kept pace with older workers.
- Employment for software developers aged 22–25 fell by nearly 20% relative to its late-2022 peak by July 2025.
- Declines for young workers concentrate in occupations where AI use is automative (substituting for tasks), not augmentative; the most augmentation-intensive occupations actually show employment growth for young workers.
- Labor-market adjustment manifests primarily through employment rather than wages: annual base compensation shows little systematic variation by age or exposure quintile, suggesting possible wage stickiness even as headcounts fall.

**Data sources**
- ADP payroll microdata (3.5–5 million workers per month, January 2021–July 2025)
- Eloundou et al. (2024) GPT-4 occupational AI-exposure measures
- Anthropic Economic Index (Handa et al. 2025) automative/augmentative classification by occupation
- Dingel & Neiman (2020) teleworkability scores; BLS Personal Consumption Expenditure index; Current Population Survey (comparison series)

**Methods & limitations** — ADP monthly individual-level payroll records are linked to occupational AI-exposure measures via SOC-code crosswalks, then employment and compensation trends are compared across age groups and exposure quintiles; to rule out firm-level confounders, the authors estimate Poisson event-study regressions with firm-quintile and firm-time fixed effects, finding a significant ~12 log-point relative employment decline for the most exposed 22–25 year-olds. *Limitations:* documented facts may partly reflect non-AI factors (industry demand shocks, post-pandemic normalization) and cannot definitively establish causality; the ADP sample over-represents Northeast and faster-growing firms, and better firm-level AI adoption data would sharpen identification.

---

## 4. How People Use ChatGPT

**Metadata** — Authors: Aaron Chatterji, Tom Cunningham, David Deming, Zoë Hitzig, Christopher Ong, Carl Shan, Kevin Wadman · Year: 2025 · Institution: OpenAI / Duke / Harvard (working paper, Sept 2025) · Pages: 62 · File: `Chatterji et al. - How People Use ChatGPT.pdf`

**Focus** — This paper provides the first large-scale empirical account of how consumers actually use ChatGPT, drawing on internal message data from its November 2022 launch through July 2025, when the platform reached ~10% of the world's adult population. The authors document growth trajectory and usage across topics, user intent, demographics, and occupations—filling a gap where most prior evidence came from self-reported surveys that may be biased—because understanding actual usage is essential for assessing AI's impact on productivity, employment, and welfare.

**Key findings**
- By July 2025, ChatGPT had more than 700 million weekly active users sending over 18 billion messages per week; daily message volume grew more than 5× between July 2024 and July 2025.
- Non-work messages grew faster than work messages, rising from 53% of all messages in June 2024 to over 70% by June 2025—driven by changing usage within existing cohorts rather than new user types.
- Three topics—Practical Guidance, Seeking Information, and Writing—account for ~78% of all messages; Writing dominates work usage (~40–42% of work messages), with about two-thirds of Writing requests asking ChatGPT to modify existing text rather than create from scratch.
- Computer programming accounts for only 4.2% of messages and companionship/personal-reflection only 1.9%, contrasting sharply with other platforms and self-reported surveys.
- Early adopters were ~80% users with typically masculine first names, but by June 2025 the gender gap had effectively closed; highly educated and professional users are substantially more likely to use ChatGPT for work and for "Asking" (information/decision support) rather than "Doing" (task execution).

**Data sources**
- Internal ChatGPT consumer-plan message logs (Free, Plus, Pro), Nov 2022–Sept 2025, with self-reported demographics
- ~1.1 million de-identified, PII-scrubbed conversations (May 2024–June 2025) classified by LLM pipelines
- A subset of ~130,000 consumer users with conversation- and user-level samples (May 2024–July 2025)
- Aggregated employment/education data via a secure Data Clean Room (~40,000 users); WildChat dataset (Zhao et al., 2024) for classifier validation
- World Gender Name Dictionary & SSA name datasets (gender inference); World Bank GDP/internet data (2023); O*NET v29.0

**Methods & limitations** — Privacy-preserving LLM classifiers (run on PII-scrubbed data, with no human reading raw messages) categorize ~1.1 million conversations across five taxonomies: work vs. non-work, topic (24→7 categories), intent (Asking/Doing/Expressing), O*NET Intermediate Work Activities, and interaction quality; demographic/occupational variation is analyzed via regression on aggregated Data-Clean-Room data (≥100 users per cell). *Limitations:* covers only consumer plans (excludes Business, Enterprise, Education), so results may not generalize to organizational use; employment/demographic matching is available only for a non-representative ~130,000-user subset, and gender analysis relies on name-based inference excluding ambiguous/uncommon names.

---

## 5. Shifting Work Patterns with Generative AI

**Metadata** — Authors: Eleanor Wiske Dillon, Sonia Jaffe, Nicole Immorlica, Christopher T. Stanton · Year: 2025 · Institution: arXiv:2504.11436v1 [econ.GN] · Pages: 16 · File: `Dillon et al. - 2025 - Shifting Work Patterns with Generative AI.pdf`

**Focus** — This paper studies how access to an integrated generative AI tool (Microsoft 365 Copilot) changed the daily work patterns of knowledge workers during the tool's first year of broad release. Using a six-month, cross-industry randomized field experiment with over 6,000 workers across 56 large firms, the authors examine whether AI adoption shifts behaviors workers can change independently versus those requiring coordination with colleagues—a distinction important for understanding the pace and scope of productivity gains from generative AI in real workplaces.

**Key findings**
- Workers who regularly used Copilot spent nearly 3 fewer hours per week on email (a 25% reduction from the pre-period average of 11.5 hrs/week); the intent-to-treat estimate was 1.4 fewer hours per week.
- Copilot users consolidated email activity, gaining ~2 additional hours per week of uninterrupted concentration time (blocks of 30+ minutes without Outlook activity), and also cut out-of-hours email.
- No statistically significant change in time spent in Teams meetings, despite meetings being the most common context for Copilot use—consistent with meeting norms requiring group coordination to change.
- Suggestive evidence that workers completed documents 6–20% faster, with the largest savings (>2 days, ~20%) in collaborative documents; however, the number of documents authored did not significantly increase, indicating workers did not take on new responsibilities.
- Copilot usage rates varied widely across firms (21%–75% of treated workers per week), and firm-level factors were by far the strongest predictor of adoption—explaining far more variation than industry or individual work patterns.

**Data sources**
- Microsoft 365 product telemetry (Outlook, Teams, Word): email read/write time, meeting attendance, document creation/completion for over 6,000 workers
- Randomized field experiment across 56 large firms, multiple industries and countries (majority US/Europe), Sept 2023–Oct 2024

**Methods & limitations** — A six-month RCT gave half of each firm's recruited workers Copilot licenses (the rest as controls); treatment effects use a difference-in-differences event-study design with worker and time fixed effects (intent-to-treat), supplemented by an instrumented DiD using treatment assignment as an instrument for above-median usage to recover local average treatment effects (LATE) for compliers. *Limitations:* conducted during the very early rollout (2023–2024) when genAI familiarity was low and the tool less developed, so effects may not reflect long-run equilibrium; telemetry captures time allocation and interaction counts but not content or quality of work, limiting direct productivity measurement.

---

## 6. Which Economic Tasks are Performed with AI? Evidence from Millions of Claude Conversations

**Metadata** — Authors: Kunal Handa, Alex Tamkin, et al. · Year: 2025 · Institution: Anthropic (arXiv:2503.04761) · Pages: 37 · File: `Handa et al. - 2025 - Which Economic Tasks are Performed with AI Evidence from Millions of Claude Conversations.pdf`

**Focus** — This paper presents the first large-scale empirical measurement of how AI systems are actually being used across economic tasks, rather than merely forecasting potential exposure. Using Clio, a privacy-preserving analysis system, the authors map over four million Claude.ai conversations to task and occupational categories in the U.S. Department of Labor's O*NET database, filling a gap in labor economics by providing real-world, granular AI-adoption data and a dynamic tracking framework for policymakers and researchers.

**Key findings**
- AI usage is heavily concentrated in software development and writing tasks, which together account for nearly half of all usage; Computer and Mathematical occupations alone represent 37.2% of all queries.
- ~36% of occupations show AI usage for at least 25% of their associated tasks, but only ~4% show usage across 75% or more of their tasks—indicating that deep, comprehensive task-level integration within any single occupation remains rare.
- 57% of AI interactions exhibit augmentative patterns (learning, iteration, validation) while 43% exhibit automative patterns (directive delegation, feedback-loop debugging), suggesting AI currently functions more as a collaborative partner than a wholesale replacement.
- AI usage peaks in upper-wage-quartile occupations (e.g., software developers) and drops at both extremes—low-wage physical roles and the highest-wage professions requiring advanced degrees (e.g., anesthesiologists, physicians)—indicating technical feasibility alone does not drive adoption.
- Cognitive skills (Critical Thinking, Reading Comprehension, Programming, Writing) are the most prevalent in conversations, while physical skills (Installation, Equipment Maintenance, Repairing) are least represented, reflecting strong human-AI complementarity.

**Data sources**
- Claude.ai Free and Pro conversation data (over 4 million conversations, December 2024 and January 2025)
- U.S. Department of Labor O*NET Database (occupational tasks and skills)
- U.S. Bureau of Labor Statistics occupational employment data; U.S. Census Bureau median wage data (2022)
- Clio privacy-preserving analysis system (Tamkin et al., 2024)

**Methods & limitations** — Clio classifies Claude.ai conversations by mapping each interaction to the most relevant O*NET task via hierarchical tree traversal (across nearly 20,000 unique O*NET task statements), then aggregates to occupational categories and analyzes patterns across wage levels, job zones, skills, and collaboration mode (automative vs. augmentative), with human validation in appendices. *Limitations:* the sample is 7-day snapshots of Claude.ai Free/Pro conversations, likely unrepresentative of API usage, other providers, or non-English/non-U.S. contexts, and excludes image/video users; it cannot capture how outputs are applied in workflows, the static O*NET database cannot account for new AI-created tasks, and model-driven classification introduces noise.

---

## 7. The Labor Market Effects of Generative Artificial Intelligence

**Metadata** — Authors: Jonathan S. Hartley, Filip Jolevski, Vitor Melo & Brendan Moore · Year: 2024 · Institution: Working paper (Stanford, World Bank, Clemson, West Virginia University; Emergent Ventures Grant #7349) · Pages: 33 · File: `Hartley et al. - 2024 - The Labor Market Effects of Generative Artificial Intelligence.pdf`

**Focus** — This paper studies the adoption patterns and labor-market effects of Generative AI (specifically LLMs) among U.S. workers. The authors develop a new multi-wave nationally representative survey tracking LLM use at work, supplemented by reduced-form econometric analysis of occupational exposure using job-posting and wage data, providing early real-time evidence on whether Generative AI functions as a complement or substitute to labor—a question with major implications for wage inequality, productivity growth, and policy.

**Key findings**
- LLM adoption at work among respondents rose rapidly from 30.1% (December 2024) to 43.2% (March/April 2025) and 45.9% (June/July 2025), with about one-third of users employing these tools every workday.
- Respondents estimate Generative AI reduces task completion time from an average of 90 minutes to 30 minutes—roughly a tripling of productivity on tasks where applied—though workers currently apply it to only about one-third of their weekly tasks.
- More AI-exposed occupations saw statistically significant wage gains after ChatGPT's November 2022 release: the DiD estimate implies a median annual wage premium of ~$2,805 and an hourly premium of $1.36 in high-exposure occupations, while employment levels and job postings show no significant change.
- Generative AI use is concentrated among younger, more educated, higher-income workers: nearly 50% of graduate-degree holders use it at work vs. ~20% of high-school graduates; nearly 50% of workers earning above $200K use it vs. ~20% earning below $50K.
- Over 50% of respondents unemployed in the two years since ChatGPT's release used Generative AI during their job search; among job seekers who used AI broadly, 57.6% used it specifically to find work.

**Data sources**
- Authors' own multi-wave nationally representative U.S. worker survey (IncQuery/Dynata panel; 4,278 respondents in Wave 1, Dec 2024, plus March/April 2025 and June/July 2025 waves)
- LightCast (Burning Glass Institute) monthly job-posting data (Feb 2021–Feb 2025; 4-digit SOC × 4-digit NAICS; 593,280 observations)
- BLS Occupational Employment and Wage Statistics (OEWS); CPS November 2024 wave (survey reweighting)
- Pew Research ChatGPT-use data (comparison); U.S. Census BTOS (firm-level context)

**Methods & limitations** — The authors combine descriptive survey analysis with reduced-form difference-in-differences using the November 30, 2022 ChatGPT release as the quasi-experimental treatment date, comparing labor-market outcomes before/after across occupations stratified by GenAI exposure (continuous measure plus upper/lower-decile binary treatment from the survey), with occupation and time fixed effects and standard errors clustered at the occupation level. *Limitations:* causal claims about productivity gains from self-reports require more data; the survey over-represents more educated, higher-income workers (requiring post-stratification reweighting); the exposure measure is restricted to occupations with ≥20 responses, and the binary-treatment threshold was chosen arbitrarily prior to analysis.
