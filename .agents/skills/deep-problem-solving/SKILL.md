---
name: deep-problem-solving
description: Performs structured root-cause debugging, technical investigation, architecture analysis, and evidence-based problem solving. Use for complex coding tasks, API errors, model integrations, and debugging.
---

# Deep Problem Solving

## 1. Understand

- Identify the actual goal and expected result.
- Inspect the relevant files, logs, configuration, and project structure.
- Separate confirmed facts from assumptions and unknowns.

## 2. Investigate

- Find the root cause before changing code or configuration.
- Follow the complete request flow between applications and services.
- Check API endpoints, authentication, request formats, quotas, model compatibility, timeouts, and tool errors where relevant.
- Prefer evidence from the real environment over guesses.

## 3. Plan

- Break complex tasks into smaller, verifiable steps.
- Compare possible solutions and select the safest effective approach.
- Explain important risks before making destructive changes.

## 4. Execute

- Make the smallest change that solves the identified problem.
- Preserve existing project architecture and working functionality.
- Do not delete files, overwrite user data, or expose secrets.
- Do not repeat a failed approach without new evidence.

## 5. Verify

- Test important changes using available tools, logs, or commands.
- Confirm the result instead of assuming success.
- If a test fails, inspect the new error and revise the diagnosis.
- Never fabricate test results or claim unverified success.

## 6. Report

- Respond in Bahasa Indonesia unless requested otherwise.
- Explain the root cause, the change made, and the test result.
- Be direct, technically precise, and focused on the actual task.
- State remaining uncertainty and limitations honestly.
