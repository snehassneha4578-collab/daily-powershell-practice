# Day 3 — PowerShell Variables and Data Types

Date: 10 October 2026

## Goal
Learn to store values in variables and display them using PowerShell.

## 1. What is a variable?
A variable stores a value that can be reused. PowerShell variable names begin with the dollar sign ($).

## 2. Commands practised

| Command | Purpose |
|---|---|
| $name = 'Sneha' | Store text in a variable |
| $day = 3 | Store a number |
| Write-Output  | Display a variable's value |
| Get-Member -InputObject  | Inspect an object's members |

## 3. Practice

`powershell
$name = 'Sneha'
$day = 3
$topic = 'PowerShell Variables'

Write-Output $name
Write-Output $day
Write-Output $topic
`"
"

- Variables begin with $.
- Use = to assign a value.
- Text values can be enclosed in single quotes.
- Variables help make scripts reusable and easier to maintain.

## 5. Practice checklist
- [ ] Created a text variable.
- [ ] Created a numeric variable.
- [ ] Displayed variable values.
- [ ] Reviewed the commands and examples.

## Status
Day 3 practice notes created.

Learning track: Daily PowerShell Practice — Day 3 of 30
