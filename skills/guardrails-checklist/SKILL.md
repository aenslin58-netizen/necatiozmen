git clone https://github.com/aenslin58-netizen/necatiozmen.git
cd necatiozmen
git checkout add-expo-skills
mkdir -p skills/guardrails-checklist
# create skills/guardrails-checklist/SKILL.md in any text editor
git add skills
git commit -m "Add guardrails checklist skill"
git push origin add-expo-skills

---
name: guardrails-checklist
description: Use before finalising any LeverAI build, to verify the five guardrail rails are in place.
---

# Guardrails checklist

## When to use
Before any build is declared complete.

## Steps
1. Input rails: ...
2. Dialog rails: ...
3. Retrieval rails: ...
4. Execution rails: ...
5. Output rails: ...

## Rules
- A build is not done until every rail is verified.
- Ask the user for any unknown stack detail. Never assume one.
