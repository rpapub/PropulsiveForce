# UiPath Workflow Analyzer Custom Rules – Sample Fixtures

This repository provides **sample UiPath Studio projects (fixtures)** to support the **development** of custom Workflow Analyzer rules.

Each rule is represented by a dedicated folder containing:
- A **Violation** project: demonstrates a workflow that violates the rule.
- A **NoViolation** project: demonstrates a workflow that complies with the rule.

These projects are **inputs for rule authoring**, not test outputs.

## 📁 Folder Structure

```
RuleName_or_RuleIdentifier/
├── Violation/
│   ├── project.json
│   └── Main.xaml
└── NoViolation/
│   ├── project.json
│   └── Main.xaml
```

- Each subfolder is a valid, minimal UiPath Studio project.
- Projects focus strictly on the behavior targeted by the rule.

## 🔧 Usage

Rule developers should:
1. Locate the relevant rule folder.
2. Open the `Violation` and `NoViolation` projects in UiPath Studio.
3. Use them to implement and refine rule logic.

## 📌 Contribution Guidelines

- Use the `RuleName_or_RuleId` naming convention.
- Include both **Violation** and **NoViolation** subprojects.
- Ensure projects are minimal, clear, and focused on the rule behavior.
- Optionally include a `README.md` inside each rule folder referencing the rule request metadata.

## 📄 License / Scope

- These fixtures are for **development purposes only**.
- Not intended as production workflows or full test suites.
- Use according to your organization’s contribution and usage policies.

