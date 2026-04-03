MYNTRA SHOP — Flask + SQLite Shopping App
========================================

FILES:
  app.py          ← Flask backend (all API routes)
  database.py     ← SQLite schema, seed data, DB helpers
  requirements.txt
  templates/
    index.html    ← Single-page frontend HTML
  static/
    css/style.css ← All styles
    js/db.js      ← Frontend API client (fetch wrappers)
    js/app.js     ← Frontend app logic

HOW TO RUN:
  1. pip install flask
  2. python app.py
  3. Open http://localhost:5000

DEMO LOGIN:
  Email:    demo@myntra.com
  Password: demo123

FEATURES:
  ✅ User registration & login
  ✅ Product catalogue with stock tracking
  ✅ Cart with GST + shipping calculation
  ✅ Saved cards per user (credit & debit)
  ✅ Credit card limit display
  ✅ Available balance display
  ✅ Monthly spending limit enforcement
  ✅ EMI on credit cards (3/6/9/12 months)
  ✅ UPI payment method
  ✅ APPROVED / DECLINED payment result
  ✅ Order history with items
  ✅ Transaction history
  ✅ Profile page with card stats

DATABASE (SQLite — myntrashop.db, auto-created):
  users         — registered accounts
  cards         — saved payment cards per user
  products      — catalogue with stock
  orders        — placed orders
  order_items   — line items per order
  transactions  — payment records (APPROVED/DECLINED)
