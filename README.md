# 50.003 cohort exercises

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

Open the relevant handout first. Each Node/React project has its own `package.json` and lockfile; install dependencies and run its scripts from that package's directory. Database exercises also need the local MongoDB or MySQL service and the configuration described in their handouts.

The CE10 handout deliberately includes failing and error-producing test cases as teaching examples. Check each exercise's objective when interpreting test results.

This fork preserves personal coursework changes. Review local work before considering an upstream update; the repository is maintained here as a coursework reference.
