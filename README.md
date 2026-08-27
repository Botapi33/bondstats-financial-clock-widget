# BondStats Financial Centre Clock Widget v3

Google Sites hardened mobile version.

Key change:
- On phones, the widget does not trust the iframe viewport width.
- It calculates the smallest real device/visual viewport width and explicitly constrains the document to that width.
- Mobile layout becomes five compact horizontal rows, eliminating right-side clipping.

Desktop keeps the five-card financial-centre presentation.
