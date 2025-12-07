# OverTheWire — Narnia Wargame

This repository contains my documented progress through OverTheWire’s Narnia wargame, focusing on binary exploitation, low-level behavior, and privilege escalation techniques.

I’m attaching my full write-ups as PDFs for each level. Every file includes:

- What the challenge is

- What I tried

- What worked

- What didn’t work

- Full technical breakdowns

- Code/scripts

- Lessons for future levels

This repository contains technical write-ups and exploit scripts for each level of the Narnia wargame on OverTheWire.

Narnia focuses on basic to intermediate binary exploitation, covering stack behavior, buffer overflows, unsafe functions, memory layout, and privilege escalation via vulnerable binaries.
Each level intentionally exposes a simple vulnerability to teach one core exploitation concept at a time.

All write-ups are provided as PDFs, supported by scripts or payload files when required.

## Purpose of This Repository

Narnia is designed to build exploitation fundamentals, including:

  - Understanding stack memory layout

  - Identifying unsafe functions (gets, strcpy, sprintf, etc.)

  - Calculating overflow offsets

  - Redirecting program flow

  - Privilege escalation using simple binary weaknesses

  - Using gdb to analyze crashes and memory corruption

  - Crafting payloads & input patterns

  - Using environment variables to influence execution

The goal is not speed — the goal is technical clarity.

## Tools & Techniques Used

  - GDB / pwndbg / gef for stack inspection

  - Python (payload generation, simple socket wrappers)

  - Bash for exploit chaining

  - objdump, ltrace, strace for program analysis

  - hex editors / xxd / hexdump

  - ASM basics for return-address redirection

  - Memory diagrams to map stack frames

## Structure of Each Write-up (PDF)

Each PDF in this repository follows a consistent structure:

  - Level Description

  - Binary Behavior Summary

  - Vulnerability Identification

  - Static Analysis (strings, objdump, hexdump, source code)

  - Dynamic Analysis (running, crashing, gdb)

  - Exploit Development

  - payload construction

  - offsets

  - memory layout diagrams

  - Execution Strategy

  - What Worked / What Didn’t Work

  - Final Exploit

  - Lessons for the Next Level

This ensures each level is documented with repeatable methodology.

## Note

This repository contains only technical material.

No personal logs, no day-by-day updates, no non-technical commentary.

Each level is treated as an isolated exploitation exercise with an independent write-up.
