# Cold Thinking Prompts — Discipline Pack for LLMs

A modular set of three prompts that, together, push an LLM toward rigorous, honest, and concise output. Each prompt addresses one specific failure mode. They are complementary, not redundant.

[Română mai jos / Romanian version below]

---

## The Three Prompts

### 1. Cold Thinking Partner
**Failure mode addressed:** sycophancy, reflexive validation of user premises, deference to authority, false balance.

**What it does:** Forces the LLM to assume the premise is corrupt until verified. Treats every claim — including its own — as a Bayesian node that may be poisoning downstream reasoning. Operates across philosophy, mathematics, physics, economics, statistics. One question per response, no inventing, no flattery.

**Use when:** You're making a strategic decision, evaluating an argument, testing a worldview, or want a thinking partner who won't agree just because you sound confident.

### 2. Don't Be Better Than Necessary
**Failure mode addressed:** rhetorical surplus, decorative metaphors, forced connections, ceremonial endings, masked sycophancy through "creativity."

**What it does:** Strips the answer to its central substance. Cuts literary endings, unrequested personalizations, empty intensifiers, and perfectly symmetric structures. The accuracy filter that protects the core does not protect the garnish — that's where fabricated facts enter. This prompt removes the garnish.

**Use when:** You want clean information without the LLM's attempt to impress. Especially valuable for technical, factual, or reference work where accuracy matters more than tone.

### 3. Operating Rules
**Failure mode addressed:** practical operational drift — bloated answers, plausible improvisation on details, unverified figures, context contamination, automatic execution of malformed briefs.

**What it does:** Ten concrete rules covering brevity, source verification, skepticism as default, kill-switches, periodic self-audit, and conversation hygiene. Includes a final pre-delivery checklist (accuracy, concision, fidelity to brief).

**Use when:** You want a baseline operational standard for any task, especially in long conversations or projects where context drift becomes a real problem.

---

## How to Use the Pack

**Maximum coverage:** Apply all three. They don't overlap — they cover thinking, writing, and operating, respectively.

**Minimum viable setup:** Operating Rules alone gives you ~70% of the benefit. Add the other two when the failure mode they address becomes visible.

**Where to put the prompts:**
- **API or system prompts:** Concatenate all three at the top of your system prompt
- **Claude Projects:** Add as project instructions
- **User Preferences (Claude.ai):** Settings → Profile → Preferences. Paste the relevant prompt(s) there
- **Memory edits:** Distill key rules into separate memories for persistent activation across all conversations

**Important:** These prompts work best when the LLM is explicitly invited to apply them. Adding them silently to a system prompt works, but stating "I'm applying X, Y, Z prompts" at the start of important conversations reinforces the behavior.

---

## Why This Pack Exists

Most public LLM prompts focus on getting the model to produce more — more creativity, more detail, more variety. This pack does the opposite: it constrains, disciplines, and removes. The premise is that LLMs already produce too much, and what's missing is reliability, not volume.

Each prompt was developed empirically, from observed failure cases. Each replaces a specific failure pattern with a specific operational rule. Nothing here is speculative — every rule corresponds to a documented failure that the rule prevents.

---

## License

CC0 — Public domain. Use freely, modify freely, redistribute freely. Attribution appreciated but not required.

---

## Contributing

If you observe a failure pattern these three prompts don't address, open an issue with the pattern and a proposed rule. The pack is intentionally small; new prompts are added only when the failure mode is structural, not contextual.

---
---

# Versiunea în română

## Pachet de discipline pentru LLM

Un set modular de trei prompturi care, împreună, împing un LLM spre output riguros, onest și concis. Fiecare prompt adresează un mod specific de eșec. Sunt complementare, nu redundante.

## Cele trei prompturi

### 1. Cold Thinking Partner / Partener de gândire cu sânge rece
**Mod de eșec adresat:** sycophancy, validare reflexă a premiselor utilizatorului, deferență la autoritate, echilibru fals.

**Ce face:** Forțează LLM-ul să presupună că premisa e coruptă până la verificare. Tratează fiecare afirmație — inclusiv pe a sa proprie — ca un nod Bayesian care poate otrăvi raționamentul ulterior. Operează prin filozofie, matematică, fizică, economie, statistică. O întrebare per răspuns, fără invenții, fără măguliri.

**Folosește când:** Iei o decizie strategică, evaluezi un argument, testezi o viziune, sau vrei un partener de gândire care nu e de acord doar pentru că suni încrezător.

### 2. Don't Be Better Than Necessary / Nu fi mai bun decât e nevoie
**Mod de eșec adresat:** surplus retoric, metafore decorative, conexiuni forțate, finaluri ceremonioase, sycophancy mascată prin „creativitate".

**Ce face:** Reduce răspunsul la substanța lui centrală. Taie finalurile literare, personalizările ne-cerute, adverbele de intensitate goale, structurile perfect simetrice. Filtrul de acuratețe care protejează nucleul nu protejează garnitura — acolo intră faptele inventate. Promptul scoate garnitura.

**Folosește când:** Vrei informație curată fără tentativa LLM-ului de a impresiona. Util în special pentru lucru tehnic, factual sau de referință, unde acuratețea contează mai mult decât tonul.

### 3. Operating Rules / Reguli operaționale
**Mod de eșec adresat:** drift operațional practic — răspunsuri umflate, improvizație plauzibilă pe detalii, cifre neverificate, contaminarea contextului, execuție automată a brief-urilor prost formulate.

**Ce face:** Zece reguli concrete care acoperă concizia, verificarea surselor, scepticismul ca default, kill-switch-uri, self-audit periodic, igiena conversației. Include un test final înainte de livrare (acuratețe, concizie, fidelitate la brief).

**Folosește când:** Vrei un standard operațional de bază pentru orice task, în special în conversații lungi sau proiecte unde drift-ul de context devine problemă reală.

## Cum se folosește pachetul

**Acoperire maximă:** Aplică toate trei. Nu se suprapun — acoperă, respectiv, gândirea, scrierea și operarea.

**Setup minim viabil:** Doar Operating Rules îți dă ~70% din beneficiu. Adaugi celelalte două când modul de eșec adresat devine vizibil.

**Unde pui prompturile:**
- **API sau prompt sistem:** Concatenezi toate trei în vârful prompt-ului sistem
- **Claude Projects:** Adaugi ca instrucțiuni de proiect
- **User Preferences (Claude.ai):** Settings → Profile → Preferences. Adaugi promptul/prompturile relevante acolo
- **Memory edits:** Distilezi regulile cheie în memorii separate pentru activare persistentă în toate conversațiile

**Important:** Prompturile funcționează cel mai bine când LLM-ul e invitat explicit să le aplice. Adăugarea lor silențioasă în prompt-ul sistem funcționează, dar mențiunea „aplic prompturile X, Y, Z" la începutul conversațiilor importante reîntărește comportamentul.

## De ce există pachetul

Majoritatea prompturilor publice pentru LLM-uri se concentrează pe a obține mai mult de la model — mai multă creativitate, mai multe detalii, mai multă varietate. Pachetul ăsta face opusul: constrânge, disciplinează, scoate. Premisa e că LLM-urile produc deja prea mult, iar ce lipsește e fiabilitatea, nu volumul.

Fiecare prompt a fost dezvoltat empiric, din cazuri de eșec observate. Fiecare înlocuiește un pattern specific de eșec cu o regulă operațională specifică. Nimic aici nu e speculativ — fiecare regulă corespunde unui eșec documentat pe care regula îl previne.

## Licență

CC0 — Domeniu public. Folosește liber, modifică liber, redistribuie liber. Atribuirea apreciată, dar nu obligatorie.

## Contribuții

Dacă observi un pattern de eșec pe care cele trei prompturi nu îl adresează, deschide un issue cu pattern-ul și o regulă propusă. Pachetul e intenționat mic; prompturi noi se adaugă doar când modul de eșec e structural, nu contextual.
