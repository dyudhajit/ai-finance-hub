# 1. Learn Prompting

## Overview

Artificial Intelligence is only as effective as the instructions it receives.

Just as a financial model is only as reliable as its assumptions, AI outputs are only as useful as the prompts that guide them.

Learning how to communicate effectively with AI is one of the highest-leverage skills a modern finance professional can develop.

This lesson introduces the principles of effective prompting and demonstrates how they can be applied across financial analysis, modelling, valuation, and investment research.

---

## Learning Objectives

After completing this lesson, you should be able to:

- Understand what prompts are and why they matter.
- Write structured prompts for finance tasks.
- Improve the quality and consistency of AI-generated outputs.
- Reduce hallucinations and factual errors.
- Apply prompting techniques to real finance workflows.

---

## What is a Prompt?

A prompt is simply an instruction given to an AI model.

Think of AI as a highly capable junior analyst.

If your instructions are vague, incomplete, or ambiguous, the output is likely to be equally vague.

If your instructions are clear, specific, and well-structured, the output becomes significantly more useful.

Good prompting is not about using complicated words.

It is about communicating clearly.

---

## Why Prompting Matters in Finance

Finance professionals work with information that must be:

- Accurate
- Structured
- Evidence-based
- Reproducible

Unlike creative writing, finance has little tolerance for ambiguity.

Poor prompts often result in:

- Missing assumptions
- Incorrect calculations
- Unsupported conclusions
- Generic responses
- Hallucinated information

Well-designed prompts improve both the quality and reliability of AI-generated work.

---

## The Anatomy of an Effective Prompt

A high-quality prompt typically contains five components.

### 1. Role

Tell the AI who it should be.

Example:

> Act as an Equity Research Analyst.

or

> Act as an Investment Banking Associate.

---

### 2. Context

Provide the necessary background.

Example:

> You are analysing Breville Group's FY2025 Annual Report to assess the company's financial performance and valuation.

Context reduces ambiguity and helps the AI produce more relevant responses.

---

### 3. Task

Describe exactly what you want the AI to do.

Instead of:

> Analyse this company.

Try:

> Identify the primary revenue drivers, key risks, and margin trends from the annual report.

Specific tasks produce better outputs.

---

### 4. Constraints

Define the boundaries.

Examples:

- Use only information contained in the annual report.
- Do not make assumptions that are not explicitly supported.
- Present findings as bullet points.
- Limit the response to 500 words.

Constraints improve consistency and reduce hallucinations.

---

### 5. Output Format

Specify how the response should be structured.

For example:

- Executive Summary
- Bullet Points
- Markdown Table
- Excel Formula
- JSON
- Investment Memo

Well-defined output formats save time and improve readability.

---

## A Simple Prompt Framework

A useful framework for finance professionals is:

```
Role

↓

Context

↓

Task

↓

Constraints

↓

Output Format
```

Example:

> Act as an Equity Research Analyst.

> You are reviewing Breville Group's FY2025 Annual Report.

> Identify the three most important business risks discussed by management.

> Use only information contained within the report.

> Present the results as a table with Risk, Evidence and Potential Financial Impact.

---

## Example: Poor Prompt

> Summarise Breville.

Possible outcome:

- Generic information
- Limited detail
- Inconsistent structure
- Unsupported assumptions

---

## Example: Improved Prompt

> Act as a senior equity research analyst.

> Review Breville Group's FY2025 Annual Report.

> Summarise the company's business model, revenue drivers, operating margins, geographic exposure, competitive advantages and key investment risks.

> Use only evidence from the annual report.

> Present the response as an executive summary suitable for an investment committee.

Notice how the improved prompt clearly defines:

- Role
- Context
- Task
- Constraints
- Output format

---

## Prompting is an Iterative Process

Rarely does the first prompt produce the perfect result.

Professional prompting follows an iterative workflow.

```
Prompt

↓

Review Output

↓

Identify Gaps

↓

Refine Prompt

↓

Repeat
```

Each iteration improves the quality of the analysis.

---

## Common Prompting Mistakes

### Asking Multiple Questions at Once

Avoid:

> Analyse Breville, build a DCF, estimate WACC, explain the industry and compare competitors.

Instead, break complex tasks into smaller steps.

---

### Being Too Vague

Avoid:

> Explain DCF.

Instead:

> Explain how Discounted Cash Flow valuation is used to estimate enterprise value, including Free Cash Flow, WACC and Terminal Value.

---

### Assuming AI Knows Your Context

Always provide:

- Company
- Reporting period
- Objective
- Audience

Context matters.

---

### Accepting the First Response

Always review:

- Assumptions
- Calculations
- Sources
- Logic
- Consistency

AI should support professional judgement—not replace it.

---

## Prompting in the AI Finance Lab

Throughout this lab, prompting will be used to:

- Analyse annual reports
- Extract financial information
- Generate modelling assumptions
- Build financial models
- Review Excel formulas
- Audit financial models
- Draft investment memos
- Prepare management presentations

Prompting is not a standalone skill.

It is embedded into every stage of the finance workflow.

---

## Key Takeaways

- Prompting is the process of communicating effectively with AI.
- Clear prompts produce better outputs.
- Structured prompts reduce ambiguity.
- Prompting is iterative.
- Professional judgement remains essential.
- AI should augment—not replace—the finance professional.

---

## Try It Yourself — Breville Case Study

Open the **Breville FY2025 Annual Report** included in this repository under the **Case Studies > Breville Group** section.

Using your preferred AI assistant, write prompts that answer the following questions:

- What does Breville do?
- How does the company generate revenue?
- What are the company's primary brands and products?
- Which geographic markets contribute most to revenue?
- What competitive advantages does management highlight?
- What risks are discussed in the report?

Compare the AI-generated responses with the annual report and refine your prompts until the answers are accurate, well-structured, and supported by evidence.

> **Goal:** Learn how better prompts produce better financial analysis.

---

## Next Steps

Continue to **Learn Auditing**, where you will learn how to critically evaluate AI-generated outputs, identify errors, and validate results before relying on them in professional finance work.

---