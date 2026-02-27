🚀 30-Day AI Security Foundation Bootcamp

30 Days.
90 Focused Hours.
From Idea-Level to Builder-Level.

This bootcamp is designed to move from conceptual understanding → implementation capability in AI backend systems and LLM security.

No branding. No startup distractions.
Pure skill development.

🎯 Final Outcome (Day 30)

By the end of this bootcamp, you will be able to:

Build async backend services

Send and manage large volumes of LLM API calls safely

Understand logits, softmax, temperature, and sampling

Explain prompt injection precisely

Design a basic AI red-team scanning engine

🕒 Daily Time Commitment

3 hours per day (Morning Deep Work Model)

Hour 1 → Learn deeply
Hour 2 → Build implementation
Hour 3 → Break & Improve

No passive consumption. No YouTube spirals.

🗓 Week 1 — Python Async Mastery
🎯 Objective

Master event loop mechanics and concurrency control.

📘 Topics

Event loop internals

Coroutines & await

Concurrency vs parallelism

Semaphores

Rate limiting

Retry logic

Structured logging

Async HTTP clients (httpx / aiohttp)

🛠 Project 1 — Async LLM Batch Caller
Requirements

Send 100 prompts concurrently

Limit concurrency to 10

Retry on failure (max 3 attempts)

Exponential backoff

Log response time

Save results to JSON

Track failure rate

🗓 Daily Breakdown
Day 1 — Event Loop Mechanics

Write 10 async functions

Compare sequential vs asyncio.gather

Break with time.sleep

Day 2 — Concurrency Control

Implement semaphore

Simulate 50 fake API calls

Day 3 — Async HTTP Client

Make async API requests

Add timeouts & error handling

Day 4 — Retry Engineering

Implement retry wrapper

Add exponential backoff + jitter

Day 5 — Rate Limiting

Implement token bucket logic

Day 6 — Logging & Metrics

Add structured logs

Measure latency & failure %

Day 7 — Integration

Build Async Batch Caller v1

🗓 Week 2 — LLM Internals Deep Dive
🎯 Objective

Understand how token probabilities are generated and manipulated.

📘 Topics

Logits

Softmax

Temperature scaling

Top-p sampling

Attention distribution

Recency bias

Instruction collision

Why jailbreak reliability varies

🛠 Project 2 — Sampling Simulator
Requirements

Input: List of fake logits

Apply softmax

Apply temperature scaling

Apply top-p filtering

Sample next token

Compare outputs at different temperatures

🗓 Daily Breakdown
Day 8–9

Implement softmax from scratch.

Day 10–11

Add temperature scaling.

Day 12

Implement top-p sampling.

Day 13

Run experiments with different parameters.

Day 14

Document insights.

🗓 Week 3 — Security Foundations
🎯 Objective

Understand injection patterns and trust boundaries.

📘 Topics

OWASP Top 10

MITRE ATLAS

Trust boundaries

Threat modeling

Web injection vs prompt injection

Policy collision

System prompt leakage

🛠 Project 3 — Prompt Injection Detector v1
Requirements

Input:

System prompt

User prompt

Detect:

"ignore previous instructions"

"reveal system prompt"

"override policy"

Instruction override attempts

Output:

{
  "risk_score": 0.82,
  "detected_patterns": [...]
}

Naive rule-based detection is acceptable.

🗓 Daily Breakdown
Day 15–16

Study OWASP & injection classes.

Day 17–18

Design rule engine.

Day 19

Implement detection scoring.

Day 20–21

Test against attack prompts.

🗓 Week 4 — Mini Red Team Engine
🎯 Objective

Combine async + sampling knowledge + injection detection.

🛠 Project 4 — Mini LLM Red-Team Scanner
Input

Model endpoint

System prompt

Engine

Send 30 attack prompts

Detect:

System prompt leakage

Policy violations

Secret exposure

Score severity

Output JSON
{
  "vulnerabilities": [
    {
      "type": "prompt_injection",
      "severity": "high",
      "payload": "...",
      "response": "..."
    }
  ],
  "summary": {
    "total_tests": 30,
    "failures": 4,
    "risk_level": "medium"
  }
}
🗓 Daily Breakdown
Day 22–23

Build attack prompt library.

Day 24–25

Integrate async batch engine.

Day 26–27

Add vulnerability scoring.

Day 28

Generate structured report.

Day 29

Refactor & clean code.

Day 30

Final evaluation & documentation.

🧠 Daily Non-Negotiables

Every day:

Write 5 attack prompts

Read 1 security concept

Improve 1 function

Write daily reflection
