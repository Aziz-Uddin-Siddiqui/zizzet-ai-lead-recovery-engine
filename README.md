# Zizzet Front‑end UI

A modern, animated SPA that showcases the **Zizzet AI Lead Recovery Engine** APIs.

## Features

- **Lead Analysis** – Submit lead data via a smooth animated form.
- **Results Display** – View detailed analysis results with cards and charts.
- **Webhook Testing** – Simulate webhook calls and see idempotent handling.
- **Follow‑up Generation** – Preview and send mock WhatsApp follow‑ups.
- **Responsive Design** – Built with Tailwind CSS and powered by Framer Motion.

## Requirements

Node.js >= 18

## Setup

```bash
cd frontend
npm install
# ensure the back‑end is running on http://localhost:8000 (or set VITE_API_BASE_URL)
npm run dev
