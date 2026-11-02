# Day 4 — PowerShell Operators and Comparisons

Date: 02 November 2026

## Goal
Understand arithmetic, comparison, and logical operators in PowerShell.

## 1. Arithmetic operators

| Operator | Meaning | Example |
|---|---|---|
| + | Addition | 10 + 5 = 15 |
| - | Subtraction | 10 - 5 = 5 |
| * | Multiplication | 10 * 5 = 50 |
| / | Division | 10 / 5 = 2 |
| % | Remainder | 10 % 3 = 1 |

## 2. Comparison operators

| Operator | Meaning |
|---|---|
| -eq | Equal to |
| -ne | Not equal to |
| -gt | Greater than |
| -lt | Less than |
| -ge | Greater than or equal to |
| -le | Less than or equal to |

## 3. Logical operators

| Operator | Meaning |
|---|---|
| -and | Both conditions must be true |
| -or | At least one condition must be true |
| -not | Reverses a condition |

## 4. Practical examples

`powershell
$a = 10
$b = 5

$a + $b
$a * $b
$a -gt $b
$a -eq $b

($a -gt 5) -and ($b -lt 10)
`"
"

- Arithmetic operators perform mathematical calculations.
- Comparison operators return Boolean values: True or False.
- Logical operators combine or reverse conditions.
- These operators are essential for PowerShell decision-making and automation.

## 6. Practice checklist
- [ ] Understand arithmetic operators.
- [ ] Understand comparison operators.
- [ ] Understand logical operators.
- [ ] Run and verify the examples.

## Status
Learning notes created. Examples documented.

Learning track: Daily PowerShell Practice — Day 4 of 30
