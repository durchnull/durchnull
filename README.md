# Hi, I'm David

Freelance full-stack engineer in Berlin. I code agentically: I build [Macrop](https://macrop.de), a nutrition planner, and six open-source plugins for [Claude Code](https://code.claude.com) that keep your codebase honest.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?logo=claude&logoColor=white)

## Macrop — a nutrition web app

<a href="https://macrop.de"><picture><source media="(max-width: 767px)" srcset="https://raw.githubusercontent.com/durchnull/durchnull/main/assets/macrop.webp"><source srcset="https://raw.githubusercontent.com/durchnull/durchnull/main/assets/macrop.webp 4x"><img src="assets/macrop.webp" align="right" alt="Macrop's sign-in screen: an illustrated pattern of carrots, tomatoes, garlic and herbs behind a frosted card reading &quot;Macrop — Deine Woche, auf Kurs.&quot;"></picture></a>

**A weekly meal planner where the numbers can't go wrong.**

Every calorie and macro is calculated from the ingredients, never typed in — so when you swap a meal or change an ingredient, your daily totals and shopping list just stay correct. Public beta, sign-ups approved by hand.

[![Try Macrop](https://img.shields.io/badge/Try_Macrop-57606a?style=for-the-badge)](https://macrop.de)

<br clear="both">

## The Heal Suite — a Claude Code plugin

<a href="https://durchnull.github.io/heal-suite/demo-run.html"><picture><source media="(max-width: 767px)" srcset="https://raw.githubusercontent.com/durchnull/durchnull/main/assets/heal-run.webp"><source srcset="https://raw.githubusercontent.com/durchnull/durchnull/main/assets/heal-run.webp 4.4x"><img src="assets/heal-run.webp" align="right" alt="A heal run dashboard: health score 90, 62 findings across 3 high, 27 medium and 32 low, findings burden 44.6 down from 67.6, 20 preventions, 41.9M tokens across 14 healers, and a per-healer table of findings, durations and backlog headings."></picture></a>

**A repo that audits, fixes and hardens itself.**

18 healers check the code, as many as the repo needs — architecture, security, tests, docs, speed and more. They run at once and put what they find in one backlog. The suite's first two sweeps of Macrop surfaced 61 and 72 findings and cut the measured maintenance burden by a third. The mechanical fixes go out as small PRs. Problems that keep coming back become gates, so they stop. Nothing merges without you.

[![Explore](https://img.shields.io/badge/Explore-57606a?style=for-the-badge)](https://durchnull.github.io/heal-suite/) [![Sample run](https://img.shields.io/badge/Sample_run-57606a?style=for-the-badge)](https://durchnull.github.io/heal-suite/demo-run.html) [![Repository](https://img.shields.io/badge/Repository-57606a?style=for-the-badge&logo=github&logoColor=white)](https://github.com/durchnull/heal-suite)

<br clear="both">

```text
/plugin marketplace add durchnull/claude-plugins
/plugin install heal@durchnull
```

## Five more plugins

| Plugin                                              | What it does                                                                                                                       |
| --------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **[plan](https://github.com/durchnull/plan)**       | Keeps your plan docs in order: write one, rank them, check them against git, hand one to a fresh session.                          |
| **[git](https://github.com/durchnull/git)**         | Ship, promote, release. It picks up your branch names and checks from the repo.                                                    |
| **[privacy](https://github.com/durchnull/privacy)** | Stops sensitive data — bank details, tax IDs, keys, names — before it lands in a file or a chat. You get `****6013` instead.       |
| **[render](https://github.com/durchnull/render)**   | Builds single-file HTML pages from your project's config: dashboards, reports, checklists, questionnaires.                         |
| **[observe](https://github.com/durchnull/observe)** | Watches how you work, if you let it: TL;DRs, saved questions, a log of what you want to get better at. Off until you switch it on. |

All six ship from one marketplace, [durchnull/claude-plugins](https://github.com/durchnull/claude-plugins).

## Available for freelance work

Full-stack product work — TypeScript, React Native, Laravel, AI. Remote from Berlin, taking new projects.

[![durchnull.de](https://img.shields.io/badge/durchnull.de-C2410C?style=for-the-badge)](https://durchnull.de)
