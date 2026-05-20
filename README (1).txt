# CDI Business Apps Suite — Master Template Repository

**Constructive Designs Inc.**  
Private master template repository for all CDI Business Apps.

## Apps Included

| App | Folder | Description |
|-----|--------|-------------|
| Landing Page | `landing/` | CDI app suite marketing page |
| Book It | `bookit/` | Appointment booking & scheduling |
| ClientFlow CRM | `clientflow/` | Contact & deal management |
| InvoiceReady | `invoiceready/` | Invoicing & payment tracking |
| ContentPlan Pro | `contentplan/` | Social media content calendar |
| LeadCatcher | `leadcatcher/` | Lead capture & tracking |
| ProposalPro | `proposalpro/` | AI-powered proposal generator |
| ExpenseTrack | `expensetrack/` | Expense & receipt management |
| ReviewBoost | `reviewboost/` | Review request automation |

## How This Repo Works

This is the **CDI master template library**. These files are never modified
directly for clients. When a client purchases an app:

1. Copilot customizes the app (branding, colors, Supabase keys)
2. Files are pushed to the client's own private GitHub repo
3. GitHub Actions auto-deploys to their Firebase Hosting account
4. Client owns everything — CDI is invited as a collaborator

## Tech Stack

- **Frontend**: Pure HTML/CSS/JS — no build tools required
- **Auth**: Supabase (Google + GitHub OAuth)
- **Database**: Supabase PostgreSQL with Row Level Security
- **Hosting**: Firebase Hosting (client-owned accounts)
- **CI/CD**: GitHub Actions (auto-deploy on push)

---
*Maintained by Constructive Designs Inc. | constructivedesignsinc.org*
