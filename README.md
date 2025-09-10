# Ploom Multi-Market Playwright Tests

This repository contains my solution to a recruitment task. The objective was to design Playwright tests in TypeScript that are easily extendable across different markets (starting with the UK and Poland).

Implemented test cases:
1. Add a product to the cart.
2. Remove a product from the cart.
3. Verify there are no broken links or images on the product page.

The project uses a Playwright setup, page object pattern, and market-specific configuration for selectors and translations. This makes it simple to add new markets in the future with minimal changes.
