---
title: "Protocol Audit Report"
author: "Lyes Boudjabout"
date: "Month Day, Year"
subtitle: "Generated with Pandoc + Eisvogel"
keywords: [Report, Pandoc, LaTeX, Eisvogel]
lang: en
colorlinks: true
logo: logo.pdf
mainfont: "Times New Roman"
fontsize: 12pt
geometry: margin=1in
header-includes:
  - \usepackage{titling}
  - \usepackage{graphicx}
---

\begin{titlepage}
    \centering
    \begin{figure}[h]
        \centering
        \includegraphics[width=0.5\textwidth]{logo.pdf} 
    \end{figure}
    \vspace*{2cm}
    {\Huge\bfseries Protocol Audit Report\par}
    \vspace{1cm}
    {\Large Version 1.0\par}
    \vspace{2cm}
    {\Large\itshape Lyes Boudjabout\par}
    \vfill
    {\large \today\par}
\end{titlepage}

\maketitle

**Prepared by:** 

- Lyes Boudjabout

**Lead Auditors:**

- [Lyes-Boudjabout](https://github.com/Lyes-Boudjabout)

**Assisting Auditors:**
- None

# Table of Contents
- [Table of Contents](#table-of-contents)
- [Protocol Summary](#protocol-summary)
- [Disclaimer](#disclaimer)
- [Risk Classification](#risk-classification)
- [Audit Details](#audit-details)
  - [Scope](#scope)
  - [Roles](#roles)
- [Executive Summary](#executive-summary)
  - [Issues found](#issues-found)
- [Findings](#findings)
- [High](#high)
- [Medium](#medium)
- [Low](#low)
- [Informational](#informational)
- [Gas](#gas)

# Protocol Summary

# Disclaimer

Lyes makes all effort to find as many vulnerabilities in the code in the given time period, but holds no responsibilities for the findings provided in this document. A security audit by the team is not an endorsement of the underlying business or product. The audit was time-boxed and the review of the code was solely on the security aspects of the Solidity implementation of the contracts.

# Risk Classification

|            |        | Impact |        |     |
| ---------- | ------ | ------ | ------ | --- |
|            |        | High   | Medium | Low |
|            | High   | H      | H/M    | M   |
| Likelihood | Medium | H/M    | M      | M/L |
|            | Low    | M      | M/L    | L   |

I use the [CodeHawks](https://docs.codehawks.com/hawks-auditors/how-to-evaluate-a-finding-severity) severity matrix to determine severity. See the documentation for more details.

# Audit Details 

## Scope

```
./src/
|-- Contract.sol
```
- Commit Hash: GIT_HASH
- Solc Version: PRAGMA_VERSION
- Chain(s) to deploy contract to: CHAINS

## Roles

# Executive Summary
## Issues found

| Severity          | Number of issues found |
| ----------------- | ---------------------- |
| High              | X                      |
| Medium            | X                      |
| Low               | X                      |
| Info              | X                      |
| Gas Optimizations | X                      |
| Total             | X                      |

## **Findings**
## High
## Medium
## Low 
## Informational
## Gas 
