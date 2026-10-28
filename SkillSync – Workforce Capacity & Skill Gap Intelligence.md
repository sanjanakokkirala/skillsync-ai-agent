# SkillSync

Workforce capacity and skill gap intelligence · Demo company: TCS-style delivery unit · 60 employees, 5 projects, 12 weeks (synthetic)

## 1 · Weekly unfilled skill demand (FTE)

View

Red cells = project work that has no qualified, free person that week. Blank = fully staffed.

## 2 · Skill supply vs demand

## 3 · Recommended actions: internal allocation, training, hiring

## 4 · Project delivery risk

## 5 · SkillSync AI agent

## How it works (algorithm)

1\) Integrate skill profiles (proficiency 1–5), project plans, allocations, LMS and hiring data → 2) Forecast demand per skill per week from project requirements → 3) Match supply: an employee counts only if qualified (level ≥ 3) and free → 4) Allocate scarcest skills first, using the least versatile qualified people and project priority (greedy assignment; Hungarian/min-cost flow in production) → 5) Gap = demand − staffed, per skill and week → 6) Close gaps in order of cost and lead time: (a) internal reallocation, (b) train idle adjacent-skill employees (level 2 → 3, 4 weeks), (c) contract hire (3 weeks) for short gaps, (d) permanent hire (8 weeks) for long gaps → 7) Re-run the allocation to verify the plan and the reduction in delivery risk.