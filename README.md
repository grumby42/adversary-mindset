# Adversary Mindset

A curated, source-cited learning path for understanding how threat actors look at organizations: their motivations, psychology, target selection and methodology. It aims to get as close to the real attacker's head as possible without crossing the line.

> **Build:** `ADVM-20261026-1814Z` · **Stamped (UTC):** 2026-10-26T18:14Z
> **Maintainer:** Ted Gransbury · [LinkedIn](https://www.linkedin.com/in/tgransbury) · [grumbylearns.io](https://grumbylearns.io)
> Every entry links to its source. Nothing here is guessed. Dates and prices change, so confirm with the organizer before you register.

---

## How this is organized

| Lens | Question it answers | Best source type |
|---|---|---|
| 1. Inside the crew | How do real operators talk, decide, and pick targets? | Leaked internal chats and analyst write-ups |
| 2. Psychology | Why do people do this, and what makes different groups tick? | Academic courses, criminology research |
| 3. Methodology | How do they work, practiced legally? | Adversary-emulation training |
| 4. Intelligence | How do analysts model intent, opportunity and capability? | CTI training and summits |
| 5. Community | Where do practitioners and researchers meet? | Conferences and webcasts |

**Lanes:** 🟢 free and online (do now) · 🟡 paid or in-person (later / employer-funded)

---

## 1. Inside the crew: primary sources

Analyses of leaked internal chats are the highest-fidelity window into how real crews reason. Read the analyses; don't go hunting for the raw dumps.

| | Source | Why it matters |
|---|---|---|
| 🟢 | [GuidePoint GRIT: Silent Ransom Group leaked chats](https://www.guidepointsecurity.com/blog/silent-ransom-group-leaked-chats/) (Oct 2026) | 5,692 messages covering Aug 2025 to Sep 2026. The crew uses help-desk impersonation calls and recruits physical "agents" into US law firms, and extorts without encryption. It shows the cyber-physical seam in practice. The analysis cites individual messages by ID, date and speaker. |
| 🟢 | [The Record: agents sent into law firms](https://therecord.media/leaked-chats-show-russian-extortion-gang-sending-agents-to-law-firms) | Recruitment of insiders, physical access, and how negotiations went |
| 🟢 | [Security Affairs: SRG's claimed $207M](https://securityaffairs.com/?p=200719) | The money trail, and the gap between the group's opsec rules and how members actually behaved |
| 🟢 | [Veeam: Silent Ransom Group profile](https://www.veeam.com/blog/silent-ransom-group-luna-moth.html) | How the playbook moved from callback phishing to email-bombing followed by Teams calls |
| 🟢 | [KELA: The Gentlemen RaaS leak](https://www.kelacyber.com/blog/the-gentlemen-ransomware-internal-chat-leak-analysis-2026/) (2026) | Roles, affiliate model, targeting logic and use of AI. The members studied Black Basta's leaked playbooks. |
| 🟢 | [TechCrunch: Black Basta chat logs](https://techcrunch.com/2025/02/21/a-huge-trove-of-leaked-black-basta-chat-logs-expose-the-ransomware-gangs-key-members-and-victims) | Target research through a data broker (ZoomInfo), plus the gang's leadership and members |
| 🟢 | [BlackBastaGPT (Hudson Rock)](https://cybersecuritynews.com/?p=93662) | Ask questions in plain language over the leaked Black Basta messages |
| 🟢 | [Inside Conti's leaked chats](https://securitymagazine.com/articles/97379-inside-conti-ransomware-groups-leaked-chat-logs) | The baseline: a ransomware crew run like a business |

**Young English-speaking crews (Scattered Spider / "The Com"). These are relevant to aviation because the FBI has warned about them targeting airlines.**

- 🟢 [Fortune/AOL: Feds hunting teenage hacking groups](https://www.aol.com/articles/feds-hunting-teenage-hacking-groups-112700246.html): how The Com is structured, and its chaotic style of negotiating directly with executives
- 🟢 [TechCrunch: Rise and fall of Scattered Spider](https://techcrunch.com/2024/11/23/the-rise-and-fall-of-the-scattered-spider-hackers/): why the group deliberately recruits minors
- 🟢 [The Independent/AOL: Inside Scattered Spider](https://www.aol.com/inside-scattered-spider-notorious-teen-142611588.html): the FBI warning on US airlines, and help-desk impersonation

---

## 2. Psychology and motivation

| | Source | Notes |
|---|---|---|
| 🟢 | [Open University: The psychology of cybercrime](https://www.open.edu/openlearn/health-sports-psychology/psychology/the-psychology-cybercrime) | Free and self-paced, with a statement of participation. Covers offender motivations and behaviours. |
| 🟢 | [European Journal of Criminology special issue: Human Factor in Cybercrime](https://research.vu.nl/en/publications/unraveling-the-human-factor-in-cybercrime-from-fraudsters-to-vict/) (2025) | Open access. Covers emerging offender profiles and tactics. |
| 🟢 | [Conference on the Human Factor in Cybercrime](https://vu.nl/en/about-vu/faculties/faculty-of-law/more-about/conference-on-the-human-factor-in-cybercrime) | The field's core academic venue. Past talks include young-offender pathways and how criminal labour is divided. |
| 🟡 | [Wilmington University: PSY 355 Psychology of a Cyber Attacker](https://wilmu.smartcatalogiq.com/en/current/undergraduate-catalog/courses/psy-psychology/300/psy-355) | Credit-bearing. Covers social engineering and thinking like an attacker. |

---

## 3. Methodology: practiced legally

| | Source | Notes |
|---|---|---|
| 🟢 | [Antisyphon Training (Black Hills InfoSec)](https://www.antisyphontraining.com/?p=15731) | Pay-What-You-Can classes from $0, with a CEU certificate and labs. Topics include adversary emulation and attack-emulation tools such as Atomic Red Team and CALDERA. |
| 🟡 | [SANS SEC565: Red Team Operations and Adversary Emulation](https://www.sans.org/cyber-security-courses/red-team-operations-adversary-emulation/) | Leads to GRTP. Section 1 covers threat-actor analysis and planning an emulation. |

---

## 4. Intelligence: modeling the adversary

| | Source | Notes |
|---|---|---|
| 🟡 | [SANS FOR578: Cyber Threat Intelligence](https://www.sans.org/for578) | Leads to GCTI. Models an adversary's intent, opportunity and capability. |

---

## 5. Events

| | Event | When | Notes |
|---|---|---|---|
| 🟢 | [Antisyphon Anticasts](https://www.blackhillsinfosec.com/events/category/anticast/page/5) | Weekly, noon Eastern | Free webcasts |
| 🟡 | [SANS CTI Summit + OSINT Summit](https://www.sans.org/cyber-security-training-events/cyber-threat-intelligence-summit-2027) | Summit Feb 1–2, 2027, Alexandria, VA (in person) | SANS runs a [volunteer program](https://www.sans.org/cyber-security-training-events/sans-osint-summit-2027) that covers attendance |
| 🟡 | [DEF CON 35](https://forum.defcon.org/calendar) | Aug 5–8, 2027, Las Vegas | Look for the Aerospace, ICS and social-engineering communities |
| 🟡 | [Aviation ISAC Cybersecurity Summit 2027](https://www.a-isac.com/events/2027-aviation-cybersecurity-summit) | Sep 28 – Oct 1, 2027, Stockholm | Registration opens May 2027 |
| 🟡 | [IATA Cybersecurity Summit](https://www.iata.org/contentassets/5a8b31c701a140f087962b2e270d2be2/cybersecurity-summit-2026-program.pdf) | Annual | The 2026 program included a 2027 aviation threat outlook session |

---

## Suggested sequence

1. Read the GuidePoint Silent Ransom Group analysis and write a one-page case study on the cyber-physical seam.
2. Complete the Open University course, then read the European Journal of Criminology special issue.
3. Add a weekly Anticast, and take one Antisyphon adversary-emulation class.
4. Read the Gentlemen and Black Basta analyses, and compare how each crew picks its targets.
5. Later or employer-funded: the SANS CTI Summit (volunteer), DEF CON 35 or the A-ISAC Summit, then FOR578 or SEC565.

## Ground rules

- Study, analyze and emulate. Never operate against systems you don't own or aren't authorized to test.
- Use published analyses of leaked material. Don't seek out, download or redistribute raw dumps.
- Cite everything. Mark anything unverified, or leave it out.

## Changelog

| Build | Date (UTC) | Change |
|---|---|---|
| `ADVM-20261026-1814Z` | 2026-10-26 18:14Z | Maintainer name corrected to Ted Gransbury; LinkedIn link added. |
| `ADVM-20261025-1550Z` | 2026-10-25 15:50Z | Initial publish. Merges the Oct 22 first pass with the Oct 25 refresh (SRG and Gentlemen leaks, The Com, the HFC academic track, A-ISAC/IATA events, Anticasts). |
