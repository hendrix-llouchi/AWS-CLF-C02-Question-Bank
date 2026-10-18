# AWS CLF-C02 Question Bank

**Live app:** [aws-clf-c02-question-bank.vercel.app](https://aws-clf-c02-question-bank.vercel.app)

A free, single-file web app for preparing for the **AWS Certified Cloud Practitioner (CLF-C02)** exam. Open it in any browser — no build step, no dependencies, works offline once loaded.

## Disclaimer

This is an independent study tool. The practice questions are original material written for exam preparation and are not official AWS exam questions. This project is not affiliated with, sponsored, or endorsed by Amazon Web Services, Inc.

## What is inside

- **400 practice questions** covering all four CLF-C02 exam domains:
  - Cloud Concepts
  - Security and Compliance
  - Technology and Services
  - Billing and Pricing
- Questions organized into sets of 65 for focused study sessions
- Explanations revealed in review mode after each set
- Per-set scoring with a 70% pass threshold and a visual score circle
- Progress tracking across sessions (stored in your browser)

## How this maps to the real exam

| | This app | The real CLF-C02 exam |
| --- | --- | --- |
| Questions per set | 65 | 65 (50 scored, 15 unscored) |
| Time limit | none | 90 minutes |
| Pass mark | 70% per set | 700 out of 1000 (scaled score) |
| Domains | all four covered | Cloud Concepts 24%, Security and Compliance 30%, Cloud Technology and Services 34%, Billing, Pricing, and Support 12% |

Note: the 70% pass mark here is a rule of thumb, not the exam’s real scoring model — the actual exam uses a scaled 100–1000 score, so consistently clearing 70% in practice is a good sign but not a guarantee.

## Known issues

- On mobile screens, some buttons are misplaced and some text is misaligned. Mobile layout fixes are in progress.

## Repo structure

```
├── AWS_Exam_Prep.html   # The entire app — questions, styles, and logic in one file
├── vercel.json           # Routes / to the app on the live site
└── README.md             # This file
```

## Run it locally

Just open `AWS_Exam_Prep.html` in a browser. That is all.

## Deployment

The repo is linked to a Vercel project (`aws-clf-c02-question-bank`). Every push to `main` redeploys automatically.
