# Velocity Reporting

Executive dashboards for tracking Developer Velocity Work. Includes program of work across Developer Experience (DX) and AI Adoption.

## Dashboards

- **dx-executive-dashboard.html** — Weekly DX/Dev Tool Efficacy executive dashboard

## Dashboard Overview

### Key Metrics Trend
Top-level trend charts showing week-over-week performance for:
- PR Throughput
- DXI (Developer Experience Index)
- Lead Time to Change
- Deploy Frequency
- AI-configured Repos

### Program Sections

**AI Maturity**
- Blox cloud workspaces adoption
- AI repository configuration and maturity
- Autonomous PR generation and merge rates

**CI Performance & Scale**
- Mobile CI performance (Android/iOS)
- CI queue time and reliability
- Remote Build Execution (RBE) improvements

**PR Review Experience**
- PR merge time and review latency
- SOX approval workflow optimization
- AI code review tooling

**Continuous Delivery**
- Playpen adoption to reduce staging squatting
- Shared acceptance test framework

**AI Migrations**
- Large-scale AI-assisted codebase migrations
- Engineering hours saved tracking

## Usage

```bash
open dx-executive-dashboard.html
```

## Structure

Each section includes:
- Platform OKRs with DRI ownership
- Primary metrics with red/yellow/green status toward Q1 targets
- Current load metrics (where applicable)
- "In Progress" displayed where dashboards and metrics are being built out
- Summary of key work this week
- Collapsible detailed status updates
- Collapsible secondary/load metrics
