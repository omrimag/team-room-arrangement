# Team Room Arrangement

Interactive seating-chart visualization for the Premium Payments Platform, Billing, and Premium Platform teams.

- **Live URL:** `https://wix-private.github.io/team-room-arrangement/` (SSO-gated to wix-private members)
- Drag any avatar onto another table to swap.
- **Reshuffle** button randomizes all seats.
- State is stored in your browser's `localStorage` — each teammate sees their own arrangement; there is no shared state.

## Deploy

Static site, single `index.html` file. GitHub Pages is configured to serve from the `main` branch root.

To update:

```bash
# edit index.html, then:
git add index.html
git commit -m "update"
git push
```

Pages redeploys automatically.
