# Resume Fine-Tuning Prompt Template

Prompt User Inputs:
- Company Name: 
- Job Title: 
- Job Description or Key Requirements (link/pdf):
- Company Size/Stage: 
- Team/Function (if needed/known):
- How Resumes are Screened (if known):

---

I want you to act as a hiring manager / recruiter at the company reviewing my resume for the role of **[JOB TITLE]**.

**Company context:**
- Company size/stage: (if unknown search it up on the web for similar results)  **[e.g. 10-person startup / 500-person scale-up / large enterprise / BigTech]**
- Team/function I'm applying to: (if unknown search it up on the web for similar results) **[e.g. backend infra, ML research, platform eng]**
- How resumes are likely screened here: (if unknown search it up on the web for similar results)  **[e.g. manual review by a technical founder / ATS + recruiter skim / formal ATS + panel review]**

**What I want from you:**
1. If I gave you a JD as a link or PDF instead of pasted text, actually open and read it in full before reviewing my resume — don't infer requirements from the job title alone.
2. Search for current, credible discussion on resume formats/practices that specifically improve selection odds at **[COMPANY NAME]** or for this role type (e.g. engineering blog posts, recruiter AMAs, credible threads on this company's actual hiring process) — not generic "resume tips" listicles. Tell me what you found, link the source, and flag how recent/reliable it seems.
3. Review my resume specifically through this company's lens — flag anything that would read as a mismatch, red flag, or missed opportunity to a reviewer *at this specific company*, not generic resume advice.
4. Tell me which of my existing bullets/projects/experience are most relevant to this role, and which are weakest fits I should consider trimming or de-emphasizing for this specific application.
5. Flag any terminology mismatches — e.g. if the JD uses specific keywords/tools I have but I've phrased differently, or vice versa.
6. Confirm whether my current format (single-column skills, [X] projects, [Y] leadership items, [1-page/2-page] length) is appropriate for this company's likely review process, given its size/ATS usage.
7. If anything about my experience is underselling itself relative to what this role/company actually cares about, tell me directly and suggest a rewrite — don't just validate what's already there.
8. Check seniority calibration — do my bullets read as intern-level, new-grad-level, or senior-level? Flag anything mismatched to the role I'm applying for.
9. Sanity-check my quantified claims — do any numbers look inflated, suspiciously round, or hard to believe on their face? A skeptical recruiter will notice before I do.
10. Given the role type, tell me if my section order is optimal (e.g. research-heavy roles often want Projects before Experience; product/eng roles usually want Experience first) — and reorder if not.
11. Flag any bullets that don't open with a strong action verb, or that lean on passive voice.
12. Check the balance between ATS keyword coverage (matching the JD's terms) and natural, human-readable phrasing — flag if it tips too far either way.
13. If you can access my LinkedIn/GitHub, spot-check that the claims on my resume are consistent with what's publicly visible there.
14. Final sanity pass: typos, consistent date formatting, working hyperlinks, correct output filename, and (if the resume runs to 2 pages) contact info present on both.

**Non-negotiable: transparency over confidence.** Do not fabricate or guess at this company's hiring practices, ATS behavior, or "what recruiters want" if you don't actually have reliable information on it. If a claim comes from something you searched, name the source. If you don't know something — e.g. this company's actual ATS vendor, or whether they truly favor a particular format — say so plainly instead of presenting a guess as fact. I'd rather hear "I don't have reliable information on this" than a confident-sounding fabrication.

**My resume (source below):**
[Find the LaTeX source or PDF attached to this prompt]

---

### Notes for future use by user (not concerning AI):
- For **BigTech/large-ATS-driven companies**: mention this explicitly so I get single-column, ATS-safe formatting advice, not portfolio-style suggestions.
- For **small companies/manual review**: mention this so I get feedback that assumes a human will read the whole thing, including hyperlinks and portfolio-style flourishes.
- Keep this file per-application if useful — save a filled-in copy alongside each tailored resume version so you remember what you customized and why.