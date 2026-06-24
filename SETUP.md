# Setup Guide

Get your Cursor rules working in under 5 minutes.

## Prerequisites
- [Cursor IDE](https://cursor.sh) installed
- Next.js 15 project with App Router

## Installation

### Option 1 — Git Clone (Recommended)
```bash
# Clone this repo
git clone https://github.com/irsyad-aulia/nextjs-ai-saas-cursor-rules

# Copy rules to your project
cp -r nextjs-ai-saas-cursor-rules/.cursor/rules/ your-project/.cursor/rules/
```

### Option 2 — Manual Download
1. Click "Code" → "Download ZIP" on GitHub
2. Extract the `.cursor/rules/` folder
3. Paste it into your project root

## Verify Installation

Your project structure should look like this:
```
your-project/
├── .cursor/
│   └── rules/
│       ├── 001-project-context.mdc
│       ├── 010-typescript-standards.mdc
│       └── 020-nextjs-app-router.mdc
│       └── ... (premium rules)
├── app/
└── package.json
```

## Activate in Cursor

1. Open your project in Cursor
2. Open Agent Mode (`Cmd/Ctrl + Shift + I`)
3. Start a new conversation — rules load automatically
4. Verify by asking: *"What stack are we using?"*
   Cursor should answer with your exact stack without you explaining it.

## Get the Full Pack (15 rules)

👉 [Buy on Lemon Squeezy — $49](https://irsyadbuilds.lemonsqueezy.com)

Includes all 15 `.mdc` files covering: React components, Server Actions,
API Routes, Supabase, Clerk, Stripe, Vercel AI SDK, shadcn/ui,
Resend, Error Handling, Performance, and Security.

---

Questions? Reach out: [@irsyadbuilds](https://x.com/irsyadbuilds)
