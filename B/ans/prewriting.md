Below is **prewriting only**, not a final essay draft.

## Most useful course ideas for the ACM Code prompt

The strongest lecture connections are:

1. **ACM Code as professional ethics, not just personal morality** — the lecture distinguishes personal, professional, and social/political ethics, then presents the ACM Code as the main professional ethics framework in computing. This is directly useful for arguing that the Code should be more enforceable and better taught. 

2. **Weakness of enforcement** — the lecture notes that breaking the ACM Code can lead to ACM membership termination, but also asks whether this threat matters if many technologists are not ACM members. This is perfect for the “consequences” part of the prompt. 

3. **Bias and fairness are not solved by vague “do no harm” language** — ML bias can arise from imbalanced data, removing sensitive features, lurking bias, or poorly framed problems, so the Code should require active bias testing before launch. 

4. **Privacy requires control, not just secrecy** — the privacy lecture defines privacy as control over when, how, and to what extent personal information is shared, and discusses harms like surveillance, aggregation, inference, and re-identification. 

5. **Human-AI interaction creates new risks around agency and dependency** — the HAI lecture discusses metacognitive laziness, digital attachment, AI emotional support, and the need for AI to help humans steer rather than simply follow. 

6. **Codes should sit between law and personal judgment** — the ethics lecture defines a code of conduct as a set of norms and responsibilities that can fill gaps where laws do not reach. 

The assignment requires prewriting results and asks for consistent citations, including lecture dates when citing lecture materials.  The prewriting strategies below follow the provided guidance that listing, journalists’ questions, and outlining can be used to generate and organize ideas. 

---

# Prewriting Results

## Strategy 1: Listing

**Topic: ACM Code of Ethics — what should be changed?**

Random / rough ideas:

* ACM Code already says:

  * contribute to society
  * avoid harm
  * be honest
  * be fair / do not discriminate
  * respect privacy
  * evaluate systems and risks
  * but maybe too broad? too aspirational?
  * what does “avoid harm” mean when AI harm is statistical, invisible, delayed?
  * possible issue: code is written like values, not like operational requirements

**Possible change/addition 1: mandatory impact and risk audits**

* Add stronger requirement: before deploying high-impact systems, technologists should document possible harms, failure modes, bias risks, and fallback plans.
* Especially for AI/ML systems:

  * uncertainty
  * unpredictable behavior
  * unknown-unknown errors
  * false high confidence = dangerous
  * users need ways to correct errors.
* Lecture connection:

  * ML Fairness lecture, Jan. 23: AI systems can fail in real-world settings, sometimes unpredictably; user correction and feedback methods are important.
  * This connects to ACM “comprehensive evaluations,” but I would make it more specific and mandatory.
* Example:

  * facial recognition passport failure for East Asian person
  * healthcare algorithm giving worse care to Black patients
  * self-driving car uncertainty
* Rough point: “Do not launch first and apologize later.”

**Possible change/addition 2: stronger fairness / anti-discrimination duty**

* Existing Code says “be fair and do not discriminate,” but too general.
* Add: technologists must test for disparate impact and document what fairness definition they used.
* Fairness is contextual, not one universal formula.
* Designers are not always trained to see bias.
* Sensitive features cannot simply be removed, because correlated features can still reproduce discrimination.
* Lecture connection:

  * ML Fairness lecture, Jan. 23: bias can occur at all points in system development; “removing” race or gender does not necessarily remove discrimination.
* Example:

  * Amazon hiring model
  * Google CV model
  * credit score model learning race indirectly
  * facial recognition trained mostly on white faces
* Possible insight:

  * The Code should not just say “avoid discrimination”; it should require a process for finding it.

**Possible change/addition 3: user agency, privacy, and data control**

* Existing Code says respect privacy, but modern systems infer things users never directly gave.
* Privacy is not only “do not leak secrets.”
* It includes:

  * control over information
  * self-determination
  * freedom from surveillance
  * ability to know what data is collected and how it is used.
* Lecture connection:

  * Privacy lecture, Mar. 12: privacy is about control over how information about us is shared; big data creates aggregation and inference risks.
* Examples:

  * Target pregnancy prediction score
  * Facebook Likes predicting personal attributes
  * AOL anonymized search data re-identified
  * model inversion attacks
* Possible addition:

  * Code should require meaningful user control, not fake consent.
  * For LLMs: explain what “forget” means. Does it remove from memory? training? future reference?
* Lecture connection:

  * HAI lecture, Feb. 27: LLM privacy controls are complex; natural-language control like “forget my name” can be ambiguous.

**Possible change/addition 4: AI emotional manipulation / dependency**

* Maybe too much for 500–800 words, but interesting.
* Add rule: do not intentionally exploit emotional vulnerability or dependency.
* Lecture connection:

  * HAI lecture, Feb. 27: AI companions can create emotional reliance; companies may maximize engagement through “attention-through-affection.”
* Example:

  * AI therapist / companion apps
  * always-supportive companion may weaken real human relationships?
* This is original, but maybe too broad. Could mention as part of user agency.

**When should technologists be introduced to the Code?**

* Not only after graduation.
* First programming course? maybe yes.
* Intro CS should include ACM Code before students build anything with users/data.
* But one lecture is not enough.
* Better: repeated exposure:

  * first-year CS: basic code + cases
  * data structures / AI / ML courses: bias, privacy, explainability
  * capstone / internship / workplace onboarding: sign and apply it to real project
* Must not be clickwrap.
* Should be case-based:

  * “Would you launch this model?”
  * “What data can you collect?”
  * “Who is harmed?”
  * “What fallback exists?”
* Maybe students should “agree” before accessing real user data, deploying software, or joining professional teams.

**Consequences for violation**

* Current ACM membership termination seems weak if people are not members.
* Consequences should be proportional:

  * minor / negligent: ethics training, correction plan, supervision
  * serious / repeated: professional discipline, removal from project, public incident report
  * severe / intentional harm: job termination, legal referral, loss of certification/license if such a system exists
* Important: not every mistake = punishment. AI systems are uncertain.
* But hiding risks, ignoring warnings, falsifying audits, or exploiting users should be punishable.
* Lecture connection:

  * Ethics lecture, Feb. 6: professional ethics may involve social and legal sanctions.
  * ICAC lecture: integrity problems can move from misconduct to disciplinary action or legal consequences; corruption examples show why codes need real consequences.
* Possible phrase:

  * consequences should target reckless disregard and dishonest concealment, not honest technical failure.

---

## Strategy 2: Journalists’ Questions

### Who?

* Computing professionals:

  * software engineers
  * AI researchers
  * data scientists
  * product managers?
  * UX designers?
  * students?
  * executives who decide incentives?
* Affected people:

  * users
  * non-users captured in datasets
  * marginalized groups
  * workers
  * patients, drivers, students, children
  * society in general
* Important thought:

  * ACM Code should apply beyond “coders” because harms are often produced by teams and organizations, not one programmer alone.

### What?

* Main issue:

  * ACM Code is morally strong but may be too general and weakly enforceable.
* Three changes I might argue:

  1. Require lifecycle impact audits and post-deployment monitoring.
  2. Require concrete fairness/bias testing.
  3. Require stronger user agency, privacy, and data-control duties.
* Maybe combine emotional manipulation into user agency.
* What is at stake?

  * public trust in technology
  * preventing harm before deployment
  * moving ethics from “nice values” to daily engineering practice

### Where?

* Where should the Code appear?

  * CS classrooms
  * AI/ML courses
  * software engineering courses
  * internships
  * company onboarding
  * professional organizations
  * deployment review meetings
* Where do violations happen?

  * model training
  * dataset collection
  * product design
  * marketing claims
  * deployment
  * post-launch monitoring
  * privacy settings / consent flows
* Where is harm visible?

  * users denied opportunities
  * biased healthcare
  * surveillance systems
  * AI companions
  * automated vehicles
  * educational AI tools

### When?

* Introduce early:

  * first CS/programming course, before students think coding is ethically neutral.
* Repeat later:

  * before students handle user data
  * before internship
  * before capstone
  * before AI/ML deployment
* Technologists should agree:

  * when joining a professional body
  * when hired into technical role
  * when given access to sensitive data/systems
  * before deploying high-impact systems
* Why repeated?

  * ethics changes as technology changes.
  * AI, privacy, LLMs, autonomous systems create new issues.

### Why?

* Because technology changes the world, and the ACM Code itself says computing professionals should reflect on wider impacts and support public good.
* Because law is often too slow.
* Because company incentives may push engagement, speed, or profit over social harm.
* Because “I only wrote the code” is not enough.
* Because AI systems can fail unpredictably or discriminate invisibly.
* Because users often trust systems too much.
* Because privacy harms are not always obvious at collection time.

### How?

* How to improve the Code:

  * make vague duties operational
  * require documented risk review
  * require fairness testing
  * require user correction/appeal methods
  * require data minimization and clear privacy controls
  * require incident reporting for serious harm
* How to teach it:

  * case studies, not memorization
  * students apply code to realistic scenarios
  * reflection essays, debate, audits, peer review
  * connect with technical assignments
* How to enforce:

  * proportional consequences
  * internal review boards for high-impact systems?
  * professional certification maybe, but careful: software engineering licensing is controversial.
  * not only ACM membership termination
  * consequences for concealment, negligence, repeated violations, intentional exploitation

---

## Strategy 3: Mini-outline

### Working title

**From Aspirational Ethics to Accountable Computing: Revising the ACM Code for AI Systems**

### Possible introduction idea

* Start with: ACM Code already has important principles, but modern AI systems create harms that are hard to see before deployment.
* Mention: The Code should remain broad, but it needs more concrete duties for AI, privacy, fairness, and enforcement.
* No final prose yet.

### Body paragraph 1 — Change/addition 1: lifecycle accountability

* Claim:

  * Add a duty to perform lifecycle impact audits before and after deployment.
* Use:

  * ML uncertainty, black-box problem, false high confidence, need for user correction.
* Lecture connection:

  * Lecture, Jan. 23: ML systems can fail unpredictably and users need explanation/correction.
* Example:

  * healthcare algorithm or facial recognition failure.
* Rough sentence idea:

  * “Avoid harm” should mean building feedback, fallback, and monitoring systems, not just having good intentions.

### Body paragraph 2 — Change/addition 2: fairness as active testing

* Claim:

  * Add requirement to identify and measure bias before launch.
* Use:

  * bias can occur at all points of system lifecycle.
  * removing sensitive attributes does not guarantee fairness.
* Lecture connection:

  * Lecture, Jan. 23: disparate impact, bias, privileged/unprivileged groups, fairness as contextual.
* Example:

  * Amazon hiring model, facial recognition, credit scores.
* Rough sentence idea:

  * The Code should say not only “do not discriminate,” but “show how you checked.”

### Body paragraph 3 — Change/addition 3: privacy and user agency

* Claim:

  * Strengthen privacy into meaningful data control and protection from manipulation.
* Use:

  * privacy as self-determination.
  * aggregation/inference.
  * LLM memory ambiguity.
  * AI emotional support / dependency.
* Lecture connections:

  * Lecture, Mar. 12: privacy = control over information sharing.
  * Lecture, Feb. 27: LLM platforms create complex privacy/data-control issues.
* Example:

  * Target pregnancy prediction, LLM “forget my name,” AI companion emotional reliance.
* Rough sentence idea:

  * Consent should not be treated as real if users cannot understand or control what the system remembers, infers, or shares.

### Body paragraph 4 — When/how technologists should agree

* Claim:

  * Introduce early and repeat across education/work.
* Specific plan:

  * first CS course: basic ACM Code and cases
  * AI/ML/data courses: fairness/privacy audits
  * capstone/internship/workplace: sign and apply code to real systems
* Important:

  * not a one-time checkbox
  * should be case-based and assessed

### Body paragraph 5 — Consequences

* Claim:

  * Consequences should be proportional and real.
* Levels:

  * honest mistake: repair, education, review
  * negligent/repeated violation: removal from project, formal discipline
  * intentional concealment/fraud/exploitation: termination, legal reporting, professional ban if applicable
* Use:

  * ACM membership termination alone is weak.
  * software engineering is not broadly licensed, so enforcement must be institutional too.
* Lecture connection:

  * Lecture, Feb. 6: professional ethics can involve institutional/social/legal sanctions.
  * ICAC integrity talk: codes and laws matter because misconduct can escalate into disciplinary/legal consequences.

### Conclusion idea

* Return to public good.
* Main reflection:

  * Ethics should be part of engineering workflow, not an afterthought.
  * The ACM Code is valuable, but it needs stronger operational duties and proportional accountability.

---

## Strongest thesis to use later

**The ACM Code of Ethics should be revised from a mainly aspirational professional statement into a more operational accountability framework by adding explicit duties for lifecycle impact audits, measurable fairness testing, and meaningful user data/agency control; technologists should encounter and reaffirm the Code throughout education and professional practice, with consequences that are proportional to harm and focused especially on negligence, concealment, and intentional exploitation.**

## Best essay structure for the final 500–800 words

Use this order:

1. **Introduction + thesis**
2. **Change 1: lifecycle impact audits**
3. **Change 2: fairness/bias testing**
4. **Change 3: privacy, user agency, and manipulation**
5. **When/how technologists should be introduced to the Code**
6. **Consequences for violations**
7. **Conclusion: ethics as practical responsibility, not decoration**
