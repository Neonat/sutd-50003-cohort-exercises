# SUTD 50.003 — Cohort Exercises

Personal coursework and reference material for SUTD 50.003 Software Construction. This fork of [sutd50003/cohortproblems](https://github.com/sutd50003/cohortproblems) retains local exercise work alongside the upstream handouts and starter projects. The upstream [MIT licence and attribution](LICENSE) remain in place.

## Exercise index

| Folder | Contents |
| --- | --- |
| [ce1](ce1/) | Browser JavaScript, min/max inputs, callbacks and promises; [exercise handout](ce1/task1/ce1.md) and [implementation notes](ce1/README.md) |
| [ce2](ce2/) | Express and database design; [handout](ce2/ce2.md) and MongoDB-backed [task 1 project](ce2/task1/) |
| [ce3](ce3/) | AJAX and React frontend development; [handout](ce3/ce3.md), [Express/MySQL backend](ce3/ce3_q1/), [React/Vite frontend](ce3/ce3_q2/) and an earlier [deprecated frontend](ce3/ce3_q2_deprecated/) |
| [ce4](ce4/) | [Use-case exercise PDF](ce4/usecase_exercise.pdf) |
| [ce5](ce5/) | [Class-diagram PDF](ce5/class_diagram.pdf) |
| [ce6](ce6/) | [Sequence diagrams, solution class diagrams and layered architecture](ce6/ce6.md) |
| [ce10](ce10/) | [Black-box unit-testing handout](ce10/ce10.md), `findmax` implementation and Jest test cases |
| [ce11](ce11/) | [Code-based testing, coverage, mutation and fuzzing handout](ce11/ce11.md) |
| [CE3_UITests](CE3_UITests/) | Express backend and React frontend reference projects with UI/component tests |

## Working with an exercise

```bash
git clone https://github.com/Neonat/sutd-50003-cohort-exercises.git
cd sutd-50003-cohort-exercises
```

For a dependency-free starting point, open
[`ce1/task1/ce1.html`](ce1/task1/ce1.html) in a browser. The associated
[implementation notes](ce1/README.md) distinguish the submission version from
the extended MinMax interface and explain the event-loop exercise.

Open the relevant handout first. Each Node/React project has its own `package.json` and lockfile; install dependencies and run its scripts from that package's directory. Database exercises also need the local MongoDB or MySQL service and the configuration described in their handouts.

The CE10 handout deliberately includes failing and error-producing test cases as teaching examples. Check each exercise's objective when interpreting test results.

This fork preserves personal coursework changes. Review local work before considering an upstream update; the repository is maintained here as a coursework reference.

## Context and status

These are separate exercises, handouts and retained local attempts, rather than
one deployable application or a claim that every problem is complete. There is
no root-level build or test command. No exercise runtime or database setup was
revalidated for this README update.

The companion [50.003 lecture examples](https://github.com/Neonat/sutd-50003-lecture-examples)
provide the corresponding reference patterns. The upstream course repository
and MIT attribution linked above remain the source of the starter material;
local notes and exercise changes are retained in this fork.
