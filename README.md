# FundTrace 🔍

**Interactive fraud detection dashboard for tracking fund flows within a bank.**  
Built for the bank hackathon on the theme: *"Tracking of Funds within the Bank for Fraud Detection."*

---

## What It Does

FundTrace reads a synthetic bank transactions CSV, builds a **directed graph** of money flows using NetworkX, detects 4 fraud patterns using rule-based logic, assigns risk scores to each account, and displays everything on an **interactive visual dashboard** powered by Pyvis.

### Fraud Patterns Detected
| Pattern | How It Works |
|---|---|
| 🔄 Circular Flow | Money loops back to origin (classic layering) |
| 💸 Structuring | Multiple sub-₹10,000 transactions within 24 hrs |
| 💤 Dormant Account | 60+ day gap then sudden large activity |
| 🕸 Hub Account | Receives funds from 8+ different sources |

---




