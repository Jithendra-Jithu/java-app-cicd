# 📈 DevOps KPIs & Performance Goals – Capstone Project

---

## 🎯 Goal

Track and continuously improve software delivery performance by measuring 4 key DevOps KPIs.

---

## 1. Deployment Frequency

- **Definition**: How often code is deployed to production.
- **Current Baseline**: 1–2 times per week
- **Target**: ≥ 3 deployments/week
- **Tracking Method**: Azure Pipelines run history + Release timeline

---

## 2. Lead Time for Changes

- **Definition**: Time from commit → successful production deployment.
- **Current Baseline**: ~3 hours
- **Target**: ≤ 1 hour
- **Tracking Method**: Pull Request time → release time in Azure DevOps

---

## 3. Mean Time to Restore (MTTR)

- **Definition**: Average time to recover from a production incident.
- **Current Baseline**: ~2 hours
- **Target**: < 1 hour
- **Tracking Method**: Azure Monitor + Incident logs

---

## 4. Change Failure Rate

- **Definition**: % of deployments causing failures/rollbacks.
- **Current Baseline**: ~20%
- **Target**: < 15%
- **Tracking Method**: Track failed pipelines + manual incident tagging

---

## ✅ Summary Table

| KPI                   | Baseline    | Target         | Tracked By                                |
|-----------------------|-------------|----------------|-------------------------------------------|
| Deployment Frequency  | 1–2/week    | ≥ 3/week       | Azure Pipeline run history                |
| Lead Time             | ~3 hours    | ≤ 1 hour       | PR open → release complete                |
| MTTR                  | ~2 hours    | < 1 hour       | Azure Monitor + Logs                      |
| Change Failure Rate   | ~20%        | < 15%          | Pipeline failures + bug count             |
