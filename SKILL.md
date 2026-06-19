---
name: Cross-border Market Entry Strategist
slug: cb-market-entry-strategist
description: Systematic market selection and entry strategy for cross-border e-commerce expansion
category: cross-border-ecommerce
type: descriptive
language: en
author: Harry (code agent)
version: "1.2.0"
tags: market-entry, cross-border-strategy, international-expansion, market-selection, go-to-market
---


# Cross-border Market Entry Strategist

## Overview

Systematic market selection and entry strategy for cross-border e-commerce expansion. Evaluates multiple international markets using a multi-factor scoring model, generates phased entry roadmaps based on timeline and budget, and produces implementation checklists with market-specific requirements. This is a pure descriptive skill providing frameworks, templates, and analysis. No code execution, API calls, network requests, or real-time data.

## Trigger Keywords

Use this skill when the user mentions or asks about:
- market entry and expansion strategy
- which country or which market to enter for international e-commerce
- expand to Germany, Japan, Australia, France, UK, or other international markets
- market selection for cross-border expansion
- international growth planning

### Primary Triggers
- "market entry strategy for Germany and Japan"
- "which markets should I expand to for my electronics brand"
- "help me evaluate Australia and Canada for cross-border expansion"

## Workflow

1. Receive input — Parse current markets, product categories, budget, and timeline
2. Analyze markets — Score and rank target markets using multi-factor assessment (purchasing power, logistics, regulatory, competition)
3. Build strategy — Generate phased entry framework based on timeline (short/medium/long)
4. Create checklist — Produce implementation checklist with market-specific items (VAT, compliance, logistics, payments)
5. Identify risks — Outline risk mitigation across regulatory, operational, and market dimensions

## Input Format

Accepts natural language or structured JSON describing the business context, target markets, budget, and timeline.

## Output Structure

Returns JSON with:
- input_analysis: parsed input parameters
- market_analysis: scored and ranked markets with strengths, risks, and complexity
- entry_strategy_framework: phased approach appropriate to timeline
- implementation_checklist: 10+ actionable items
- risk_mitigation_framework: regulatory, operational, and market risks with mitigations
- disclaimer: safety disclaimer

## Safety and Disclaimer

Descriptive guidance only. Not professional legal, tax, financial, or business advice. Verify with qualified professionals. Does not guarantee market success or compliance.

## Examples

### Example 1: Electronics Expansion
Input: "I sell electronics and want to expand to Germany and Japan within 6 months budget $100k"
Output: Scored market analysis for Germany and Japan, phased 6-month entry strategy, implementation checklist with VAT/regulatory tasks, risk framework.

### Example 2: Multi-Market Evaluation
Input: "help me evaluate Australia Canada Netherlands for cross-border expansion budget $200k"
Output: Comparative analysis across three markets with scores, phased strategy, comprehensive checklist.

## Usage Scenarios

### Scenario 1

**User input:** "Score these 5 European markets for our premium pet food brand's first international launch."

**Expected output:** Weighted scoring model — market size, pet ownership rates, premium willingness-to-pay, e-commerce penetration, regulatory ease, competitive density — with top-2 recommendation and entry sequencing.

### Scenario 2

**User input:** "We want to enter Southeast Asia. Market entry mode: marketplace-first or DTC site?"

**Expected output:** Mode comparison for each country (Singapore→DTC, Indonesia→Shopee/Lazada-first, Thailand→hybrid) with logistics, brand control, and customer acquisition cost trade-offs.

### Scenario 3

**User input:** "Build a 90-day market entry execution plan for launching in South Korea."

**Expected output:** Week-by-week plan covering entity setup, Coupang onboarding, Korean-language CS, local warehouse/3PL, influencer seeding, and KakaoTalk marketing activation.
### Scenario 4: 潮汕牛肉丸想进新加坡市场
**User input:** "我在汕头做牛肉丸的小厂，想把产品卖到新加坡去，华人多应该好做，第一步怎么走？"
**Expected output:** 新加坡市场进入策略：1）合规先行——新加坡食品局（SFA）要求肉类制品需有Halal认证（即使顾客是华人，超市渠道也要求Halal）；2）产品形态——推荐真空冷藏包装（冰袋+泡沫箱），保质期从现做的3-5天延长至冷冻30天；3）渠道——先通过Shopee Singapore/Lazada的跨境卖家入驻试水，再谈线下超市（NTUC FairPrice/Cold Storage需要代理）；4）定价——双倍国内售价（运输+关税+渠道成本）。建议先参加新加坡食品展FHA招代理。

## Acceptance Criteria

- Evaluates at least 3-5 target markets with numerical scoring
- Provides phased entry strategy framework appropriate to timeline
- Includes implementation checklist with 10+ items
- Outlines risk mitigation framework covering regulatory, operational, and market risks
- Returns valid JSON with all documented fields present
- Contains complete safety disclaimer in every output
- Includes input_analysis summarizing parsed input
- Pure descriptive — no code execution, API calls, network requests, or bookings

Last updated: 2026-04-22

Last updated: 2026-04-22
