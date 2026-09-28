# Pundit - World Cup Prediction Game

> **Showcase page.** This repository is a public showcase of a **private repository**:
> it contains a description of the work only, with **no source code**.

A full-stack **social prediction game**: free to play, with a paid tournament pass sold through real card payments. Shipped as a web app and as native iOS and Android builds.

## What I built

- **Prediction gameplay** - predict fixtures, build a track record, compete in leagues
- **Social layer** - leagues, messages, profiles
- **Team theming** - pick a team and the whole app changes colour
- **Penalty shootout mini-game**
- **Payments** - embedded card checkout on the app's own page using Stripe's Payment Element, so card data never touches the app and the user never leaves the site; the secret key lives only in a server-side function
- **Demo mode** - the entire app runs with zero keys and faked auth, so anyone can click through it before any backend exists
- **Mobile delivery** - Capacitor shells for iOS and Android, with cloud CI producing signed iOS builds without a Mac
- **Load testing, push notifications and store-release setup**

## Stack

React, Vite, Tailwind CSS, Supabase (auth, Postgres, edge functions), Stripe (Payment Element), Capacitor, Codemagic CI, Netlify

---

*Source code is private. This page documents the work; code can be shared on request.*
