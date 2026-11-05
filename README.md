# Awuraba Frozen Foods — order page

The shop's own order page, hosted free on GitHub Pages. Everything runs in the
browser: the order form opens WhatsApp with the order written out, and the
Awuraba bot answers questions. No server, no database, nothing to pay for.

- **Customers:** open `index.html` (published at the GitHub Pages link).
- **Owner:** orders arrive as WhatsApp messages on 0501212522 — your WhatsApp
  chat is your order list.

## Changing prices or stock

Prices live in the `MENU` block near the top of `index.html` (the part marked
`===== MENU =====`). Edit a number, save, and the change is live in a minute.
Ask your agent to do it for you if you prefer.

- `available: false` = the item shows greyed out / "out of stock".
- `kg / half / box / halfbox` = prices per kg, ½kg, box (10kg), ½box.
  Leave a box empty (`""`) if you don't sell that size.
