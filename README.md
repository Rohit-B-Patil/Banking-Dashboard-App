# 💰 Banking Dashboard App (Redux Toolkit)

A clean and functional React app that simulates a bank account system, built using **Redux Toolkit (RTK)** for modern state management and classic **Redux Thunk** for async operations like currency conversion. The app offers a complete banking simulation experience with a focus on clarity, scalability, and usability.

---

## 🚀 Features

- Create and manage a personal bank account
- Deposit and withdraw funds in different currencies
- Request and repay loans with a specified purpose
- Convert foreign currencies (e.g., GBP, EUR) to USD using async API logic
- Real-time UI updates based on global state changes

---

## ⚙️ What’s Implemented

- State managed using **Redux Toolkit slices**
- **Classic Redux Thunk** used for asynchronous currency conversion
- Integrated `useDispatch` and `useSelector` hooks from React Redux
- Modular Redux architecture with clean slice separation
- Fully interactive UI reflecting all account actions
- Styling done using **standard CSS** (no UI libraries or frameworks)

---

## 🔧 Tech Stack

- React
- Redux Toolkit
- React Redux
- Redux Thunk (manual thunks)
- Plain CSS

---

## 🧱 Architecture Highlights

- Feature-based slice structure (`account`, `customer`, etc.)
- Custom async logic implemented using classic thunk middleware
- Mutative logic simplified using Immer (built into RTK)
- Developer-friendly debugging via Redux DevTools
