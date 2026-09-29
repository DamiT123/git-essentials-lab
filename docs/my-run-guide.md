# Library demo run guide

## Prerequisites
- JDK 17 or later (both `java` and `javac`)
- Python 3.9 or later
- Git

## Run the demo
From the repository root:

python3 run.py demo

## What the demo does
The demo runs a short library loan scenario using a fixed date (2026-09-01).
It prints the borrowing limits for students and faculty, searches the catalog
for "git", lends the book "Git Essentials" to a member (Alex) with a due date
of 2026-09-15, then returns it and prints the late fee (0) and the number of
active loans left (0).