# Pork & Garlic Ice Cream — Year 2 Winter Decision Tool

A responsive financial decision tool for comparing Year 2 winter strategies in the Pork & Garlic Ice Cream classroom business simulation.

## Features

- Compare multiple production and financing strategies side by side
- Calculate feasible production from milk and machine capacity
- Estimate revenue, costs, profit, tax, loan payments, and closing cash
- Test lower-sales scenarios at 100%, 80%, and 60% of the expected allocation
- Carry forward tax losses and apply them against future taxable profit
- Display warnings for capacity, liquidity, premises, and financing risks
- Verify the built-in Year 1 example against the classroom result
- Save entered information locally in the browser

## Built-in verification

The included Year 1 example reconciles to:

- Net profit/loss: **Sh -3,560**
- Closing cash: **Sh 71,940**

## Deployment

This repository contains a prebuilt static version of the application.

To deploy it with Vercel:

1. Import this GitHub repository into Vercel.
2. Select **Other** as the framework preset.
3. Use `npm run build` as the build command.
4. Use `public` as the output directory.
5. Click **Deploy**.

No environment variables or external services are required.

## Important note

The initial values are demonstration data. Replace them with your team's confirmed Year 1 results and Year 2 assumptions before making a final decision.
