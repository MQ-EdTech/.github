# MQ-EdTech

Educational technology tools built at [Macquarie University](https://www.mq.edu.au/).

We develop software that supports teaching and learning in computing courses — from automated feedback pipelines to static analysis tools for student code.

## Projects

| Repository | Description |
|------------|-------------|
| **Majordomo** | Automated student feedback pipeline — analyses Processing sketches, runs static analysis, and generates structured feedback |
| **Zita** | Static code analysis tool for Processing (Java) — extends PMD with custom rules for educational assessment |

## How It Works

```
Student submission (.pde)
        |
    Majordomo (Python/Flask)
        |
    Zita (Kotlin/Java) — static analysis via PMD
        |
    Structured feedback — rule results + LLM-generated guidance
```

## Contributing

These repositories support teaching at Macquarie University. If you're a staff member or collaborator looking to contribute, reach out to the org owners for access.

---

*Macquarie University — Faculty of Science and Engineering*
