# Maverick Bank – Updated User Interface

## Run locally
1. Extract this project folder.
2. Open a terminal in the folder containing `package.json`.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL shown by Vite.

## Included screens
### Customer
- Banking overview and existing transfer workflow
- My Accounts
- Transaction History
- Beneficiary management
- My Profile

### Administration
- Operations overview
- Customer directory and account status controls
- KYC application review
- Account management
- Transfer limit configuration
- Audit log with CSV export

The customer sign-in, dashboard, transfer submission, idempotency handling, and shared Banking Switch integration remain in the original banking component. The added administration screens and beneficiary management are client-side interface functionality; they do not create or modify protected bank records on the server.
