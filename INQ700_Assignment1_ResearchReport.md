# Closing the Awareness–Action Gap: Understanding Persistent Cyber Security Behaviour Among Australian Small Businesses

**Student Name:** Ibrahim Rasras
**Student Number:** 12482595

---

## Problem Statement

Australian small and medium businesses (SMBs) make up 97% of all businesses and are increasingly targeted by cyber criminals (Australian Cyber Security Centre [ACSC], 2020). The 2019 ACSC Small Business Survey — the most comprehensive Australian baseline available — found that although 80% of SMBs rated cyber security as important or very important, 62% had already experienced a cyber incident, almost half spent less than $500 per year on cyber security, and roughly half implemented four or fewer of the eight Essential Eight mitigation strategies (ACSC, 2020). These patterns are not merely historical: the ASD's 2024–25 Annual Cyber Threat Report records that the average self-reported cost of cybercrime to a small business reached $56,571, up 14% year-on-year, with malicious activity increasing in frequency, cost and severity (ASD, 2025). Together, the evidence describes a sector that recognises the problem yet struggles to act on it.

Across the scholarly literature a consistent "awareness–action gap" appears. High self-reported concern coexists with weak implementation of foundational controls (Bada & Nurse, 2023; Valli et al., 2014). Recent Australian work confirms the pattern persists: Chidukwani et al. (2024) found the greatest barriers for Western Australian SMBs were lack of funds and, critically, a lack of knowledge about where to begin. Internationally, Renaud and Ophoff (2021) explain this through a cyber situational-awareness model: SMEs often fail to act not because they dismiss the threat, but because they lack the situational awareness and resources to translate concern into controls.

The literature is divided on whether outsourcing improves security. The ACSC (2020) warns of a "vulnerable cohort": SMBs that outsource often believe they are better protected than they are, yet frequently implement few Essential Eight strategies. Conversely, some guidance assumes managed services lift posture. There is also tension between accounts that emphasise resource constraints (Chidukwani et al., 2024) and those emphasising behavioural and cognitive factors such as overconfidence and optimism bias (ACSC, 2020; Renaud & Ophoff, 2021).

Most empirical SME cyber-security research originates outside Australia (UK, Europe), and the Australian-specific evidence that exists is now dated (Dojkovski et al., 2010; Valli et al., 2014; ACSC, 2020). Tam et al. (2021) explicitly conclude there is a gap in current, reusable Australian small-business cyber-security research and call for context-specific investigation. It therefore remains unclear whether the behavioural patterns — the awareness–action gap, overconfidence, and reliance on ad-hoc do-it-yourself approaches — documented in 2019 still characterise Australian small businesses today.

There is a lack of current, Australian-specific evidence on whether the awareness–action gap and the risk-perception biases (overconfidence, optimism bias, and reliance on do-it-yourself approaches) identified in the 2019 ACSC Small Business Survey persist among Australian small businesses, and on how these behavioural factors continue to impede adoption of foundational cyber security controls.

---

## Approach

I used a structured, iterative search strategy across five sources accessed through the QUT Library: Summon (Library SuperSearch), Scopus, Web of Science Core Collection, IEEE Xplore, and Google Scholar (the latter for government and grey literature such as ACSC and ASD reports). The aim was to locate authoritative, mostly peer-reviewed sources on SME cyber security, with a deliberate emphasis on the Australian context and on the behavioural dimensions highlighted by the ACSC baseline.

Exact Boolean queries (not merely keywords):

- **Q1:** `("small business*" OR SME OR "small and medium enterpris*") AND ("cyber security" OR cybersecurity OR "information security") AND (Austral*)`
- **Q2:** `("small business*" OR SME) AND ("cyber security" OR cybersecurity) AND (aware* OR attitude* OR perception* OR "risk perception")`
- **Q3:** `("small business*" OR SME) AND ("cyber security" OR cybersecurity) AND (implement* OR adopt* OR "mitigation strateg*" OR "Essential Eight")`
- **Q4:** `("small business*" OR SME) AND ("cyber security" OR cybersecurity) AND (outsourc* OR "do-it-yourself" OR DIY OR "in-house")`
- **Q5:** `("small business*" OR SME) AND ("cyber security" OR cybersecurity) AND (overconfid* OR "optimism bias" OR "availability heuristic" OR "situational awareness")`

Refinements and why they worked: My initial Q1 returned a large, predominantly non-Australian corpus; adding the `Austral*` truncation dramatically improved precision by isolating the small set of locally relevant studies (ACSC, 2020; Chidukwani et al., 2024; Valli et al., 2014; Dojkovski et al., 2010). I restricted the timeframe to 2010–2025 to ensure currency while retaining foundational Australian work. Using synonym groups (`cyber security`/`cybersecurity`; `small business`/SME) captured variant indexing across databases, whereas a single-term search missed key papers. I separated awareness (Q2) from implementation (Q3) to mirror the ACSC's own distinction and to expose the awareness–action gap as a discrete theme, and I broadened Q5 to behavioural-theory terms because SME cyber-security research frequently sits within behavioural security rather than purely technical venues. Excluding large-enterprise-only studies kept the sample on-topic.

Organisation: I grouped the literature into five themes that reflect the central issues: (1) the awareness–action gap; (2) risk perception and cognitive biases; (3) outsourcing versus DIY and the "vulnerable cohort"; (4) the Australian contextual and cultural setting; and (5) research gaps in Australian-specific, reusable evidence. This thematic logic connects each source to the research problem rather than listing papers chronologically.

Key references and their relevance to the problem: **ACSC (2020)** supplies the baseline gaps my problem interrogates; **Tam et al. (2021)** explicitly establish the Australian research gap, justifying novelty; **Renaud and Ophoff (2021)** provide the situational-awareness lens explaining inaction, justifying the behavioural framing; **Chidukwani et al. (2024)** supply current Australian evidence that the "where to start" barrier persists, supporting importance and currency; **Valli et al. (2014)** and **Dojkovski et al. (2010)** show the awareness–action gap and cultural factors are long-standing, supporting that the problem is persistent; **Bada and Nurse (2023)** document the confidence–practice disconnect underpinning the bias theme. More recent empirical work — **Rand et al. (2026)** and **Khan et al. (2025)** — supplies 2024–25 evidence that risk underestimation and inconsistent guidance persist, directly supporting the currency and importance of the problem, while **Voce and Morgan (2025)** provide current Australian evidence that SME ransomware victims suffer disproportionately.

---

## Literature Review

Combining my own reading with CoPilot-assisted analysis of the retrieved corpus, five themes emerge.

**Theme 1 — The awareness–action gap (own analysis).** The ACSC (2020) baseline shows 80% of SMBs rate cyber security important yet nearly half implement four or fewer Essential Eight strategies. Valli et al. (2014) and Bada and Nurse (2023) report the same disconnect in Australian and UK samples, indicating concern rarely converts to control adoption. Recent work confirms the pattern persists: Rand et al. (2026) found SMEs underestimate risk and are unsure where to find support, while Voce and Morgan (2025) report Australian SME ransomware victims faced wider device compromise and repeated targeting. This is the central, agreed finding of the field.

**Theme 2 — Resource constraints versus behavioural causes (own analysis).** Chidukwani et al. (2024) attribute non-adoption chiefly to limited funds and not knowing where to start, whereas the ACSC (2020) and Renaud and Ophoff (2021) foreground cognitive factors. The literature thus disagrees on primacy: structural resourcing versus psychological barriers. Khan et al. (2025) locate a further barrier in the guidance itself: the volume and inconsistency of online advice leaves SMEs confused about what to implement, reinforcing the "where to start" problem.

**Theme 3 — Outsourcing paradox and the "vulnerable cohort" (CoPilot-assisted).** CoPilot surfaced the ACSC's (2020) counter-intuitive finding that outsourced SMBs often feel better protected while implementing few Essential Eight strategies. This contradicts practitioner guidance that treats managed services as protective, yet Chidukwani et al. (2024) report IT service providers are among SMBs' most-used guidance sources — suggesting outsourcing is simultaneously the layperson's default remedy and, per the ACSC, a potential blind spot when owners cease monitoring what their provider does. Whether outsourcing genuinely lifts posture or manufactures false confidence is therefore unresolved.

**Theme 4 — Cognitive biases in risk perception (CoPilot-assisted).** Synthesising across sources, CoPilot highlighted optimism bias, overconfidence, and the availability heuristic (ACSC, 2020) and the situational-awareness deficit (Renaud & Ophoff, 2021) as mechanisms explaining why SMEs underestimate likelihood and recovery time. Renaud and Ophoff position situational awareness as the mediator between knowing security is "important" and actually implementing controls. Supporting this, Bada and Nurse (2023) found SME self-rated optimism about their security routinely exceeded their actual practice — the confidence–practice disconnect. Roughly one in five SMBs were "possibly overconfident" despite poor practices (ACSC, 2020), indicating the bias is not marginal but substantial.

**Theme 5 — Sparse, dated, non-reusable Australian evidence (own analysis).** Tam et al. (2021) argue Australian small-business cyber-security research is narrow and lacks reusability, while Dojkovski et al. (2010) and Valli et al. (2014) are now over a decade old. This consensus on a research gap validates the need for current, context-specific work.

**Synthesis.** The state of the art shows a robust, cross-national awareness–action gap, with Australian evidence suggesting the pattern is entrenched by cultural ("she'll be right") and resource factors (Dojkovski et al., 2010; Chidukwani et al., 2024). There is broad agreement that concern does not equal action, but clear disagreement on why: structural-resource accounts (Chidukwani et al., 2024) compete with behavioural-cognitive accounts (ACSC, 2020; Renaud & Ophoff, 2021), and the value of outsourcing remains contested. Importantly, no study has re-measured the specific behavioural patterns the ACSC documented in 2019 — overconfidence, optimism, DIY reliance, and low Essential Eight uptake — against today's evolved threat landscape and newer guidance such as the Cyber Wardens program, leaving a clear gap that the research problem addresses.

---

## Conclusions

The literature establishes, with strong agreement, that SMBs recognise cyber security's importance but under-implement foundational controls (ACSC, 2020; Bada & Nurse, 2023; Valli et al., 2014). Renaud and Ophoff's (2021) situational-awareness model and the ACSC's (2020) confidence profiles together explain this gap through limited awareness and optimistic risk perception rather than outright indifference. Chidukwani et al. (2024) confirm these barriers remain current in the Australian context, and Tam et al. (2021) confirm the corresponding research gap.

It is important to investigate this problem because Australian SMBs represent 97% of businesses and face rising, costly cyber threats, yet the behavioural drivers of their inaction are poorly understood and largely unmeasured since 2019. Closing this evidence gap can inform guidance, such as the ACSC's Essential Eight and the Cyber Wardens program, that actually changes behaviour rather than merely raising awareness. The problem is both novel (Australian-specific, behavioural, and current) and solvable through a survey-based replication of the ACSC instrument combined with the situational-awareness lens of Renaud and Ophoff (2021), making it feasible within a student research project.

Reflecting on process, CoPilot accelerated thematic grouping and surfaced non-obvious connections (the outsourcing paradox, the clustering of cognitive biases), whereas my manual reading was essential for judging source authority, Australian relevance, and the credibility of statistics against the original ACSC report. Used together, the two approaches produced a more balanced review than either alone; used uncritically, CoPilot's suggestions risk over-generalisation, which is why every claim was verified against primary sources.

---

## References

Australian Cyber Security Centre. (2020). *Cyber Security and Australian Small Businesses: Results from the Australian Cyber Security Centre Small Business Survey*. Australian Signals Directorate. https://www.cyber.gov.au/sites/default/files/2023-03/2023_ACSC_Cyber%20Security%20and%20Australian%20Small%20Businesses%20Survey%20Results_D1.pdf

Australian Signals Directorate. (2025). *Annual Cyber Threat Report 2024–2025*. Australian Government. https://www.cyber.gov.au/about-us/view-all-content/reports-and-statistics/annual-cyber-threat-report-2024-2025

Bada, M., & Nurse, J. R. C. (2023). Cybersecurity awareness and capacities of SMEs. In *Proceedings of the International Conference on Information Systems Security and Privacy (ICISSP 2023)*. SCITEPRESS. https://doi.org/10.5220/0011609600003405

Chidukwani, A., Zander, S., & Koutsakis, P. (2024). Cybersecurity preparedness of small-to-medium businesses: A Western Australia study with broader implications. *Computers & Security, 145*, 104026. https://doi.org/10.1016/j.cose.2024.104026

Dojkovski, S., Lichtenstein, S., & Warren, M. J. (2010). Enabling information security culture: Influences and challenges for Australian SMEs. In *Proceedings of the 21st Australasian Conference on Information Systems (ACIS 2010)*.

Renaud, K., & Ophoff, J. (2021). A cyber situational awareness model to predict the implementation of cyber security controls and precautions by SMEs. *Organizational Cybersecurity Journal: Practice, Process and People, 1*(1), 24–46. https://doi.org/10.1108/ocj-03-2021-0004

Tam, T., Rao, A., & Hall, J. L. (2021). The good, the bad and the missing: A narrative review of cyber-security implications for Australian small businesses. *arXiv*. https://arxiv.org/abs/2109.00733

Valli, C., Martinus, I. C., & Johnstone, M. N. (2014). Small to medium enterprise cyber security awareness: An initial survey of Western Australian business. In *Proceedings of the International Conference on Security and Management* (pp. 71–75). CSREA Press.

Khan, N., Furnell, S., Bada, M., Nurse, J. R. C., & Rand, M. (2025). The hidden barriers to cyber security adoption amongst small and medium-sized enterprises. *Information and Computer Security*. https://doi.org/10.1108/ICS-04-2025-0135

Rand, M., Bada, M., Furnell, S., Nurse, J. R. C., & Khan, N. (2026). Understanding cyber security practices in SMEs: A mixed-methods investigation. *Information Security Journal: A Global Perspective*, 1–39. https://doi.org/10.1080/19393555.2026.2648174

Voce, I., & Morgan, A. (2025). Ransomware targeting individuals and small businesses: Vulnerabilities and impacts. *Trends & Issues in Crime and Criminal Justice*, No. 724. Australian Institute of Criminology. https://doi.org/10.52922/ti78106
