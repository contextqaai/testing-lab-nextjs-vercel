# ContextQA lab — Next.js · Vercel dashboard

Educational source fork of [vercel/next-learn](https://github.com/vercel/next-learn). Original history, notices and license are retained. This is not an endorsed integration or a customer production app.

**Status: source and exercises available. Public deployment, platform import and ContextQA run results are not verified.**

Starting source commit: `bb2558441a6673ab76c89914c25018bffa27a2ba`.

## Setup and scope

Use dashboard/final-example for the completed course example rather than dashboard/starter-example. Configure the required database and authentication environment privately before Vercel import. Source setup is available; no Vercel deployment has been performed.

Follow the [original setup instructions](../README.md#upstream-project-documentation). See [stack/platform guidance](https://github.com/contextqaai/testing-lab/blob/main/PLATFORMS.md) for deployment boundaries.

## Exercises

| Scenario | Explicit assertion |
|---|---|
| Sign in | The configured synthetic user reaches the dashboard. |
| Create invoice | A new fixture invoice records the intended customer, amount and status. |
| Search | The new invoice appears under its matching query. |
| Edit invoice | The selected invoice update is visible after reload. |
| Preview regression | The same assertion detects a disclosed regression on the explicitly selected preview deployment. |

These are acceptance exercises, not claims that upstream currently satisfies each desired requirement. Inspect the implemented workflow and fixtures before generating executable steps. Missing validation/auth may deliberately demonstrate a failure and must be disclosed.

## End-to-end lesson

Start an owned/authorized copy with synthetic fixtures. State the assertion, create/review a test in your authenticated ContextQA workspace, execute, and inspect the actual verdict. Introduce one disclosed regression in a separate variant, rerun the same assertion, fix the app and rerun. Confirm mutations against disposable data. Keep credentials and private reports out of this repository.

Record app commit/build, fixture/scenario version, browser/runner version, environment and timestamp with every real report. A cached report is recorded evidence, not a new run. No ContextQA report has been generated for this fork yet.

[ContextQA setup](https://contextqa.com/tutorials/getting-started-with-contextqa-test-automation/) · [Central catalog](https://github.com/contextqaai/testing-lab)
