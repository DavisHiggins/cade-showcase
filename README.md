<p align="center">
  <a href="https://cade.davishiggins.com"><img src="assets/hero.svg" width="100%" alt="Cade: built to remember, directed by me. Animated cover with the Cade wordmark beside a five-step loop (Orient, Retrieve, Prime, Execute, Persist) that lights up in sequence around a swirling memory field." /></a>
</p>

<h1 align="center">Cade</h1>

<p align="center"><strong>A persistent AI working partner built around structured memory, focused retrieval, and reusable Jobs.</strong></p>

<p align="center">
  <a href="https://cade.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="Explore Cade" /></a>&nbsp;
  <a href="https://www.higginsd.com/work/cade"><img src="assets/btn-case.svg" height="44" alt="Case study" /></a>&nbsp;
  <a href="https://davishiggins.com"><img src="assets/btn-dh.svg" height="44" alt="Davis Higgins" /></a>
</p>

<p align="center"><sub>In daily use · Designed and built by Davis Higgins</sub></p>

---

## See it in motion

<p align="center">
  <img src="assets/demo.gif" width="880" alt="Screen recording of cade.davishiggins.com: scrolling through the operating-loop chapter as an orange circle fills and steps through Orient, Retrieve, Prime, Execute, and Persist." />
</p>

<p align="center"><sub>Real capture of the public site's operating-loop chapter. <a href="assets/demo.png">Static frame</a></sub></p>

## What it does

- **Remembers between sessions.** Projects, decisions, standards, and lessons persist, so work picks up where it left off instead of being re-explained.
- **Loads only what a task needs.** Cade pulls the smallest useful slice of context for the job in front of it, and everything else stays one search away.
- **Turns repeated work into Jobs.** Recurring work becomes a reusable Job that carries the procedure, the quality bar, and the lessons from every earlier attempt.

## Why I built it

I kept re-explaining the same projects, decisions, and standards to an assistant that forgot them the moment a chat ended. For anything ongoing, re-explaining cost more than the answer was worth.

The fix wasn't a better model. It was giving the model a durable place to keep what it learns and a disciplined way to read it back before it acts. Now analytics, builds, coursework, and career work continue instead of restarting.

## What I built

- The memory system and how it's organized
- The operating loop that governs when Cade reads, acts, and writes back
- The Job format, and the Jobs I use for analytics, development, and writing
- The public site at cade.davishiggins.com, designed to explain the system without exposing it

<details>
<summary><strong>How it's put together</strong></summary>

<br />

```mermaid
flowchart TB
    O[Orient] --> R[Retrieve]
    R --> P[Prime]
    P --> E[Execute<br/>with me directing]
    E --> S[Persist]
    S -. every session starts stronger .-> O
```

| Decision | Why |
|---|---|
| **Memory I own** | Cade's knowledge is readable and portable, so it's useful on its own and I can audit or correct anything by hand. |
| **Small context, on purpose** | Cade loads only what a task calls for, which keeps answers focused and leaves room for the work itself. |
| **I stay in control** | Consequential actions need my confirmation, outside content is treated as information rather than instructions, and access only grows when I grant it. |

</details>

## Screens

<table>
  <tr>
    <td width="62%"><img src="assets/screenshot-home.png" alt="Cade homepage: 'One system. Every workflow.' in black on a bright orange field." /></td>
    <td rowspan="2" width="38%" align="center"><img src="assets/screenshot-mobile.png" width="300" alt="Cade homepage on a phone with the 'Explore the system' and 'Build your own' buttons." /></td>
  </tr>
  <tr>
    <td><img src="assets/screenshot-jobs.png" alt="Cade Jobs chapter: 'Read one Job. Have the whole skill.'" /></td>
  </tr>
</table>

<sub>Homepage · The Jobs chapter · Homepage on mobile</sub>

## Technology

| Part | Technology |
|---|---|
| Assistant | Claude |
| Public site | Next.js, React, TypeScript |
| Motion | GSAP, Lenis, Three.js |
| Hosting | Vercel |

---

<p align="center">
  <a href="https://cade.davishiggins.com"><img src="assets/btn-open.svg" height="44" alt="Explore Cade" /></a>&nbsp;
  <a href="https://github.com/DavisHiggins"><img src="assets/btn-more.svg" height="44" alt="More of my work" /></a>
</p>

<p align="center"><sub>© 2026 Davis Higgins. All rights reserved. The Cade name and logo belong to Davis Higgins.</sub></p>
