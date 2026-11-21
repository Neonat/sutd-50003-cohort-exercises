# Software Construction cohort exercises | SUTD 50.003

This coursework fork keeps local exercise attempts alongside the SUTD 50.003 handouts. Start with the [plain MinMax submission](ce1/task1/ce1.html), then try the [extended MinMax page](ce1/task1/minmax/minmax.html). Both open directly in a browser. The extended version adds input checks, a random list, and a search-style interface. The [development notes](ce1/README.md) record how the original loop kept losing the current minimum and maximum.

## Choose an exercise

| Topic | Exercise materials |
| --- | --- |
| Browser events and asynchronous JavaScript | [CE1](ce1/) starts with form input and a click handler, then moves on to callbacks, promises, and the event loop. |
| A database-backed API | [CE2](ce2/task1/README.md) uses TypeScript and Express for a department and staff API. MongoDB records which department each staff member belongs to. |
| Client and server | [CE3](ce3/ce3.md) separates an [Express/MySQL backend](ce3/ce3_q1/) from a [React frontend](ce3/ce3_q2/) served by Vite. The exercise connects department and staff views to API data. An [earlier frontend](ce3/ce3_q2_deprecated/) remains for reference. |
| Modelling before implementation | [CE4](ce4/usecase_exercise.pdf) covers use cases, [CE5](ce5/class_diagram.pdf) covers class diagrams, and [CE6](ce6/ce6.md) adds sequence diagrams and layered architecture. |
| Tests and their failure modes | [CE10](ce10/ce10.md) uses Jest to test a maximum-finding function. The handout calls for both a failing assertion and an uncaught error. [CE11](ce11/ce11.md) covers coverage, mutation, and fuzzing. The [CE3 UI test examples](CE3_UITests/) pair a backend with frontend tests. |

## Run a teaching example

From the repository root, use Node.js and npm to run the CE10 test package.

```sh
cd ce10/ce10
npm ci
npm test
```

The checked-in test bodies are empty. The handout asks students to supply the assertions and observe the difference between a failed assertion and an uncaught error. The other Node projects have their own packages and scripts. The database exercises also need their matching MongoDB or MySQL setup. There is no shared root test command.

The upstream [cohort problems](https://github.com/sutd50003/cohortproblems) are copyright © 2024 SUTD 50003 under the [MIT licence](LICENSE). For the corresponding reference implementations, see the [50.003 lecture examples](https://github.com/Neonat/sutd-50003-lecture-examples).
