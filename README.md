🌐 P!VOT (Pivot Web)
P!VOT is a high-performance, modern web application designed for the next generation of telecommunications management. It features a Unified Device Interface (UDI) that allows users to seamlessly manage data balances, perform secure transfers, and handle mobile data like a transferable digital asset.

"Send data like money. Control it like currency."

🚀 Core Vision
Pivot transforms mobile data into a transferable digital asset, enabling peer-to-peer data sharing through a unified system. It bridges users with the future of decentralized connectivity by turning unused data into tradable value.

✨ Key Features
🔌 Unified Device Interface (UDI)
Multi-Device Management: Register and track multiple devices (Phones, Laptops, Tablets) under one account.
Unique UDI Identifiers: Each device receives a unique @UDI handle (e.g., @user-iphone) for targeted data management.
Real-Time Tracking: Monitor data consumption, connection status, and linked phone numbers for every device in your fleet.
💸 Data & Financial Management
Instant Data Transfers: Send data balance to other P!VOT users via their phone number or UDI handle.
Pivot Points System: Integrated virtual currency where 15 fragments = 1 Pivot Point, used as gas fees for transactions.
Wallet & Transactions: Full transaction history for both data recharges and wallet-based financial operations.
Custom Recharge Plans: Users can create and manage personalized data plans instead of fixed telecom packs.
📊 Dashboard & Insights
Transaction History: Comprehensive log of all data and wallet activities.
Usage Insights: Track data balance and daily consumption patterns.
Dynamic Fee Mechanism: Lower fees for same-network transfers, higher for cross-network transactions.
🔐 Secure & Scalable
Advanced Auth: Powered by Better-Auth for secure sessions, account linking, and multi-factor authentication support.
Admin Dashboard: Comprehensive management tools for user balances, system setup, and recharge operations.
Real-Time Notifications: Instant alerts for data transfers, system updates, and account activity.
🛠️ Technical Stack
Framework: Next.js 15+ (App Router, Turbopack)
Database: Turso (Edge-ready SQLite)
ORM: Drizzle ORM (Type-safe database management)
Authentication: Better-Auth
Payments: Stripe
Billing/Usage: Autumn-js
UI/UX: Tailwind CSS, Radix UI, Framer Motion
Icons: Lucide React, Tabler Icons
🏗️ Database Architecture
The system uses a robust relational schema optimized for speed and consistency:

Table	Description
users	Core user profiles, data balances, and primary UDI.
udi_devices	Registered hardware linked to user accounts.
transactions	Ledger of data transfers and plan purchases.
wallet_transactions	Financial history for the integrated wallet.
recharge_plans	Active and historical data plans for each user.
usage_history	Granular daily data consumption tracking.
notifications	User-specific real-time system alerts.
🚦 Getting Started
1. Prerequisites
Node.js (Latest LTS)
npm or bun
2. Environment Setup
Create a .env file in the root directory:

TURSO_CONNECTION_URL=your_turso_url
TURSO_AUTH_TOKEN=your_turso_token
BETTER_AUTH_SECRET=your_auth_secret
STRIPE_TEST_KEY=your_stripe_key
AUTUMN_SECRET_KEY=your_autumn_key
3. Installation
npm install --legacy-peer-deps
4. Running the App
npm run dev
Open http://localhost:3000 to view the application.

🌱 Future Enhancements
📡 Real-time telecom integration
🔗 Blockchain-based transaction verification
🤖 AI-powered usage optimization
🌍 Cross-platform sync (mobile + web)
🛡️ Security Note
The P!VOT team prioritizes security. Please ensure that all .env files are added to .gitignore and that API endpoints are protected using session-based authorization checks.

Built with ❤️ for the P!VOT Network.
