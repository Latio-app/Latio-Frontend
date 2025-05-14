# 🌎 Latio
Borderless Payments. Boundless Travel.

Latio is a next-generation cross-border payment platform powered by Stellar Soroban, designed to make global transactions fast, secure, and borderless. With Latio, international travelers and LATAM locals can exchange currencies, manage budgets, and explore new destinations without financial friction.

## 🚀 Features
Passkey Kit Authentication: Secure passwordless login for instant wallet access.

Real-Time Wallet Management: View XLM and local currency balances instantly.

Seamless Currency Swaps: Low-cost, real-time cross-border transactions.

Travel Planner: AI-powered travel recommendations and budget planning.

Global Payments for Local Merchants: Accept international payments easily.

## 🛠️ Tech Stack
Technology	Purpose
Next.js 13 (App Router)	Modern React-based frontend framework
TailwindCSS	Utility-first CSS for rapid UI development
Firestore (NoSQL)	Real-time database for user data and travel
Stellar SDK	Interact with Stellar blockchain and Soroban
Passkey Kit	Passwordless wallet authentication
Zustand	State management for session and wallet
TypeScript	Static typing for error-free development

## 📂 Project Structure
```
📂 src
 ├── 📂 app                    # Next.js App Router
 │   ├── layout.tsx            # Main layout
 │   ├── page.tsx              # Main dashboard
 │   ├── 📂 wallet
 │   │   └── page.tsx          # Wallet overview and balance
 │   ├── 📂 travel
 │   │   ├── page.tsx          # Travel planner
 │   │   └── [id]
 │   │       └── page.tsx      # Travel detail page
 │   ├── 📂 transactions
 │   │   └── page.tsx          # Transaction history
 │   ├── 📂 recommendations
 │   │   └── page.tsx          # AI-driven travel insights
 │   └── 📂 api
 │       ├── auth
 │       │   └── route.ts      # Login & Passkey Kit integration
 │       ├── wallet
 │       │   └── route.ts      # Wallet API
 │       ├── transaction
 │       │   └── route.ts      # Transactions API
 │       └── travel
 │           └── route.ts      # Travel Planner API
```
## 🌐 Environment Variables
Make sure to create a .env file with the following variables:
```
NEXT_PUBLIC_FIREBASE_API_KEY=your-api-key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-auth-domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-storage-bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your-messaging-id
NEXT_PUBLIC_FIREBASE_APP_ID=your-app-id

PASSKEY_KIT_API_URL=https://passkey-kit.io
PASSKEY_KIT_CLIENT_ID=your-client-id
```
🚀 Getting Started
### 1️⃣ Clone the repository:

```
git clone https://github.com/yourusername/latio-frontend.git
cd latio-frontend
```
### 2️⃣ Install dependencies:

```
pnpm install
```
### 3️⃣ Run the application:
```
pnpm dev
```
### 4️⃣ Visit the app:
Open http://localhost:3000 in your browser

### 🔄 Development Workflow
Main Branch: main → Stable releases

Development Branch: dev → Active development

Feature Branches:

feature/wallet-integration

feature/travel-planner

feature/transaction-history

Create a new feature branch:
```
git checkout -b feature/wallet-integration
```
Push changes:

```
git add .
git commit -m "Add wallet integration"
git push origin feature/wallet-integration
```
### ✅ Planned Features:
 Wallet Overview and Management

 Secure Cross-Border Transactions

 Travel Planner with AI Recommendations

 Real-Time Budget Tracking

 Local Merchant Payments

### 🤝 Contributing
Feel free to open issues, submit PRs, and suggest features!

Fork the repo

Create your feature branch (git checkout -b feature/my-feature)

Commit your changes (git commit -m 'Add my feature')

Push to the branch (git push origin feature/my-feature)

Open a Pull Request

### 🔒 Security & Privacy
Latio leverages Passkey Kit and Stellar Soroban for decentralized, secure transactions. Your financial data is encrypted and protected at every step.

# 🏷️ License
Latio is licensed under the MIT License.

