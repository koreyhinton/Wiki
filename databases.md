# Databases
## Functional Dependency
[Functional Dependency Quiz](https://lagunita.stanford.edu/courses/DB/RD/SelfPaced/courseware/ch-relational_design_theory/seq-quiz-fd/)

[Normalization Quiz](https://lagunita.stanford.edu/courses/DB/RD/SelfPaced/courseware/ch-relational_design_theory/seq-quiz-norm/)

## Conflicts

If the database is read-only:
- serializable - no conflicts
- repeatable read - no conflicts

To prove it is serializable we can give another serializable schedule (or show no cycles in precedence graph)

A schedule looks like: T2, T3, T4
