# Digital Asset Trading Platform

TradeSphere is a self-hosted cryptocurrency trading platform sold by Coderobotics as complete, unencrypted source code. It is built with PHP 8.3, Laravel 13, Livewire 4, Alpine.js, Tailwind CSS 4 and MySQL 8 or MariaDB 10.11+, with Laravel Reverb for real-time updates. The platform combines five trading modes in one application: SPOT (market, limit and stop-limit orders with a price-time-priority matching engine), P2P with escrow and disputes, Binary Higher/Lower, perpetual Futures with leverage and liquidation, and Copy Trading. All balances run through an immutable double-entry ledger across Funding, Spot, Futures, Copy and demo wallets. It also includes deposits and withdrawals through Stripe, NOWPayments and Coinbase Commerce, KYC with encrypted documents, two-factor authentication, multi-level referrals, notifications by email, SMS and browser push, a CMS, a REST API and an admin panel with 30+ management modules. TradeSphere installs as a Progressive Web App with dark and light themes and ships with 106 automated tests. It suits startups, agencies and brokers who want to launch a branded exchange. Operators must supply their own payment gateway accounts, liquidity provider and regulatory compliance, and real-money Binary and Futures trading are disabled by default.

<img src="https://www.coderobotics.com/frontend/assets/icon/TradeSphere_Digital_Asset_Trading_Platform.jpg">

TradeSphere is a self-hosted cryptocurrency trading platform with SPOT, P2P, Binary, Futures and Copy Trading in one Laravel application. It includes multi-wallet management on a double-entry ledger, payment gateway integrations, KYC, referrals, a CMS and a full admin panel. Install it on your own server, configure your assets and gateways, and run your own branded exchange as a Progressive Web App with dark and light themes.

Building an exchange from scratch means writing a matching engine, a wallet ledger, payment integrations, KYC flows and an admin back office before the first trade happens. TradeSphere ships all of that as complete source code. It covers five trading modes, every balance movement goes through an immutable double-entry ledger, and 106 automated tests (539 assertions) cover the platform’s acceptance criteria.

What You Get
 
SPOT trading – market, limit and stop-limit orders, a price-time-priority matching engine, order book, trade history, charts and an optional operator-funded liquidity ladder
P2P trading – advertisements, escrow-protected orders, payment windows, chat with attachments, disputes and evidence
Binary trading – Higher/Lower with configurable durations and payouts, deterministic timestamped settlement and a demo mode
Futures trading – independent perpetual engine with leverage, isolated/cross margin, stop-loss/take-profit, funding, liquidation and a demo mode
Copy trading – trader profiles, allocations, per-trade caps, stop-loss and historical performance
Wallets and ledger – Funding, Spot, Futures, Copy and separate demo wallets, balance holds, and a double-entry ledger with reversals, idempotency keys and a reconciliation command
Deposits and withdrawals – manual crypto and bank, plus Stripe, NOWPayments and Coinbase Commerce adapters with signed, idempotent webhooks, limits, fees and risk-based withdrawal review
Accounts and security – email verification, TOTP 2FA with recovery codes, Google and MetaMask sign-in, login history, session management, phone verification and an anti-phishing code
KYC – submissions with encrypted data and documents, admin review and retention purge
Referrals – multi-level commissions settled through the ledger
Notifications and support – in-app, email, browser push and SMS with editable templates, plus support tickets with internal notes
CMS – pages, blog, FAQ, announcements, banners, menus, homepage sections, SEO metadata and sitemap
Admin panel – dashboard, roles and permissions, 30+ management modules, reports with CSV/Excel/PDF export, audit logs and system health
REST API v1 – personal access tokens with ability scopes
Demo data seeder – sample customers with activity in every module
Documentation – installation, production deployment and compliance checklist, API and webhooks, and a developer guide

Why This Platform?
 
Most exchange scripts cover one trading mode and keep balances in a single editable column. TradeSphere is built the way financial software should be.

Five trading modes in one codebase, sharing one wallet system
Every balance change is a ledger entry you can audit and reconcile
Real money Binary and leveraged Futures are disabled by default until you enable them
Demo wallets let users practise without touching real funds
Installable PWA with consistent dark and light themes
Complete, unencrypted Laravel source code you can extend

Perfect For
 
Startups launching a branded crypto exchange
Fintech agencies delivering trading platforms for clients
P2P marketplace operators who need escrow and dispute handling
Brokers who want to offer copy trading or demo trading
Developers studying matching engines, ledgers and margin systems
Teams that need a working base to customise instead of starting from zero

Tech Stack
 
PHP 8.3
Laravel 13
Livewire 4
Alpine.js
Tailwind CSS 4
Vite
MySQL 8 / MariaDB 10.11+
Laravel Reverb (real-time updates)
CoinGecko (live market prices)

Prerequisites
 
PHP 8.3 with Composer
Node.js and npm
MySQL 8 or MariaDB 10.11+
A server that can run the scheduler, a queue worker and the Reverb real-time server
Your own accounts for the services you want to use: Stripe, NOWPayments, Coinbase Commerce, Google sign-in, Twilio SMS and an email provider. These integrations are built and tested with simulated data and need your credentials to go live.
A liquidity provider for SPOT markets, and your own deposit addresses and bank details
Load testing on your production hardware before launch (not yet performed on this release)
Compliance notice: TradeSphere is software infrastructure, not a licence to operate. Before accepting customer funds you must arrange custody, payment, liquidity and compliance (KYC/AML, licensing) for your jurisdiction.

Frequently Asked Questions – TradeSphere
 
1. What is TradeSphere?
TradeSphere is a self-hosted cryptocurrency trading platform built with Laravel. It includes SPOT, P2P, Binary, Futures and Copy Trading, along with wallets, payment gateways, KYC, referrals, a CMS and a full admin panel.

2. Do I get the complete source code?
Yes. You receive the full, unencrypted source code with no domain limitations, so you can customise it as you need.

3. What technology is it built with?
PHP 8.3, Laravel 13, Livewire 4, Alpine.js, Tailwind CSS 4, Vite and MySQL 8 or MariaDB 10.11+. Real-time updates use Laravel Reverb.

4. What are the server requirements?
You need PHP 8.3, Composer, Node.js with npm, and MySQL 8 or MariaDB 10.11+. The server must also be able to run the scheduler, a queue worker and the Reverb real-time server, so a VPS or dedicated server is recommended over basic shared hosting.

5. Which trading modes are included?

SPOT with market, limit and stop-limit orders
P2P with escrow, chat and disputes
Binary Higher/Lower
Perpetual Futures with leverage, margin and liquidation
Copy Trading with allocations and stop-loss
6. Can users practise without real money?
Yes. Binary and Futures have a demo mode with separate demo wallets, so users can trade without touching real funds.

7. Are real-money Binary and Futures trading enabled out of the box?
No. Both are disabled by default. You can enable them from the admin panel once you have confirmed they are permitted in your jurisdiction.

8. Which payment gateways are supported?
Stripe, NOWPayments and Coinbase Commerce, plus manual crypto and bank deposits. The gateway integrations are built and tested with simulated data, and you connect them with your own accounts and webhook URLs before going live.

9. Where do market prices come from?
Live prices are fetched from CoinGecko. For real SPOT markets you connect your own liquidity provider, or use the optional operator-funded liquidity ladder.

10. How are user balances kept accurate?
Every balance change is recorded in an immutable double-entry ledger with reversals and idempotency keys. A reconciliation command verifies that all transactions balance and that wallet balances match the ledger.

11. What security features are included?
Email verification, TOTP two-factor authentication with recovery codes, login history, session management, phone verification, an anti-phishing code, encrypted KYC data, role-based admin permissions and audit logs.

12. Does it include KYC?
Yes. Users submit KYC details and documents, which are stored encrypted. Admins review submissions, and a retention purge removes old data.

13. Is there a mobile app?
TradeSphere is a Progressive Web App. Users can install it on their phone or desktop from the browser, with dark and light themes and browser push notifications. There are no separate native Android or iOS apps.

14. Does it have an API?
Yes. A REST API (v1) with personal access tokens and ability scopes is included, along with API and webhook documentation.

15. Is the platform tested?
The automated suite has 106 tests with 539 assertions, all passing. Performance and load testing has not been done yet, so you should run load tests on your own production hardware before launch.

16. Does buying TradeSphere give me a licence to run an exchange?
No. TradeSphere is software only. You are responsible for custody, payments, liquidity and regulatory compliance (KYC/AML, licensing) in your jurisdiction before accepting customer funds.

17. Can I use it for multiple projects or resell it?
No. The regular license covers a single project, for yourself or a client. Resale and distribution of the source files are not allowed.

18. Is installation included?
Installation is not free. Charges range from $5 to $10, depending on the software’s complexity and criticality. Installation documentation is included if you prefer to set it up yourself.

19. What support and updates do I get?
Unlimited email support for one year and free updates for one year.

20. How soon will I receive the source code after payment?
The download link is sent within 2-4 hours on working days (Monday–Friday) and within 4-8 hours on weekends.

21. Is it a one-time payment?
Yes. After your full payment you receive the complete source code, and no additional payments are required.

More details & download link:
https://www.coderobotics.com/product/digital-asset-trading-platform
