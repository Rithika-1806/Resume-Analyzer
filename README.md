# 🧇 Waffles & Cream Website

## Files
- `index.html` — Main website
- `styles.css` — All styles
- `app.js` — Cart logic + Supabase + Razorpay

---

## ⚙️ Setup Instructions

### Step 1 — Supabase Setup
1. Go to https://supabase.com → Create a new project
2. Open **SQL Editor** and paste the SQL from the browser console (open DevTools → Console)
3. Go to **Project Settings → API** and copy:
   - **Project URL** → paste into `SUPABASE_URL` in `app.js`
   - **anon/public key** → paste into `SUPABASE_ANON_KEY` in `app.js`

### Step 2 — Razorpay Setup
1. Go to https://razorpay.com → Create account
2. Go to **Settings → API Keys** → Generate Key
3. Copy **Key ID** → paste into `RAZORPAY_KEY_ID` in `app.js`
4. Use `rzp_test_...` for testing, `rzp_live_...` for live payments
5. For production: Create Razorpay orders from your backend (Node.js) for signature verification

### Step 3 — Deploy
- Upload all 3 files to any web host (Netlify, Vercel, etc.)
- Or use Netlify Drop: drag the folder to https://app.netlify.com/drop

---

## 📋 Viewing Orders (Supabase Dashboard)
- Go to Supabase → **Table Editor** → `orders`
- All paid orders will appear here with customer details

## 📱 Features
- ✅ Full menu from actual menu card
- ✅ Add to cart with quantity control
- ✅ Bubble Waffle builder (choose base + filling)
- ✅ Checkout form with delivery/pickup
- ✅ Razorpay payment (UPI, Cards, NetBanking)
- ✅ Order saved to Supabase
- ✅ Success screen with payment ID
- ✅ Fully responsive (mobile-friendly)
- ✅ Smooth animations & scroll reveal
