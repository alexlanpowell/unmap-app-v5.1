# 🗺️ Unmap - Event Discovery & Business Platform v5.1

![Version](https://img.shields.io/badge/version-5.1-blue)
![React Native](https://img.shields.io/badge/React%20Native-0.81.5-61DAFB?logo=react)
![React](https://img.shields.io/badge/React-19.1.0-61DAFB?logo=react)
![Expo](https://img.shields.io/badge/Expo-54.0.22-000020?logo=expo)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.2-3178C6?logo=typescript)
![Supabase](https://img.shields.io/badge/Supabase-Backend-3ECF8E?logo=supabase)
![Stripe](https://img.shields.io/badge/Stripe-Payments-635BFF?logo=stripe)

> **⚠️ IMPORTANT: This app requires EAS Development Builds. It no longer works with Expo Go due to native modules (Stripe, Camera, Maps, etc.).**

Unmap is a premium, production-ready event discovery and business monetization platform built with React Native and Expo. Discover events on an interactive map, create business pages, sell tickets, collaborate with teams, and connect with your community. Version 5.1 introduces a complete viral growth system, enhanced payment features, instant payouts, TOTP authentication, and development build architecture for production deployment.

---

## 📋 Table of Contents

- [What's New in V5.1](#-whats-new-in-v51)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Platform Support](#-platform-support)
- [Getting Started](#-getting-started)
- [Development Workflow](#-development-workflow)
- [Project Structure](#-project-structure)
- [Architecture Overview](#-architecture-overview)
- [Authentication System](#-authentication-system)
- [Payment & Payout System](#-payment--payout-system)
- [Database Schema](#-database-schema)
- [Design Principles](#-design-principles)
- [Performance Metrics](#-performance-metrics)
- [Known Issues](#-known-issues)
- [Contributing](#-contributing)
- [Support](#-support)
- [License](#-license)

---

## 🎯 What's New in V5.1

### 🔐 Enhanced Authentication (NEW)
- **TOTP (Time-Based One-Time Password)**: Two-factor authentication using authenticator apps
- **Email + OTP Flow**: Secure email verification with OTP codes
- **Phone Number Onboarding**: Multi-step onboarding with phone verification
- **Password Management**: Secure password creation with strength validation
- **Session Management**: Robust session handling and security

### 🚀 Viral Growth & Referral System
- **Complete Referral System**: Users earn bonuses for referring friends (10¢ per signup, $2 per business creation)
- **Viral Share Messages**: 20 casual, friend-to-friend messages that drive app downloads
- **Referral Dashboard**: Track clicks, conversions, and earnings in real-time
- **Deep Linking**: Branch.io integration for attribution tracking
- **Analytics**: Message performance tracking and leaderboard

### 💳 Enhanced Payment Features
- **Inline Ticket Purchase**: Seamless ticket buying experience integrated into event details
- **Instant Payouts**: Fast payment processing with Stripe Connect (4% fee for ~30 minute payouts)
- **Standard Payouts**: Free daily/weekly/monthly payout options
- **Wallet Integration**: User wallets for managing earnings and payments
- **Bank Account Sync**: Easy payout management for businesses
- **Transaction History**: Complete view of all purchases and earnings
- **Payment Methods**: Save and manage multiple payment methods
- **Platform Commission**: Automatic fee calculation and distribution

### 🛠️ Development Build Architecture (BREAKING CHANGE)
- **No Expo Go Support**: Requires custom development builds via EAS
- **Full Native Module Access**: Camera, Stripe payments, advanced maps, push notifications
- **TestFlight Distribution**: iOS testing via TestFlight for friends and family
- **APK Distribution**: Android testing via direct APK installation
- **Hot Reload**: Fast iteration with production-like features
- **Over-the-Air Updates**: EAS Update for instant JavaScript updates

### 🏢 Business Management Enhancements
- **Multi-Business Support**: Create and manage multiple business pages
- **Team Management**: Role-based permissions (Owner, Admin, Manager, Editor, Analyst, Event Creator)
- **Financial Permissions**: Granular control over billing, revenue viewing, and subscriptions
- **Business Settings**: Configure auto-collaboration preferences and limits
- **Audit Logs**: Track all changes made to business pages
- **Business Visibility Controls**: Choose which businesses to display publicly
- **Revenue Dashboards**: Comprehensive analytics with charts and exports

### 🐛 Bug Fixes & Stability
- **Map Toggle Crash Fix**: Resolved critical crash when switching map views
- **Username/Bio Validation**: Improved validation and error handling
- **Wallet Improvements**: Fixed transaction display and balance calculations
- **Profile Sharing**: Fixed iOS link duplication in share messages
- **Image Upload**: Enhanced reliability with timeout and retry logic
- **Date/Time Handling**: Fixed timezone bugs with component-based date construction

---

*[Full README content continues with all sections...]*

For the complete documentation, see the main [Unmap-App repository](https://github.com/alexlanpowell/Unmap-App).