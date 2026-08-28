# BondStats Financial Centre Clock Widget v4

This build fixes Google Sites mobile clipping by not trusting the iframe viewport on touch devices.

Mobile behaviour:
- Locks the document to a conservative safe width (max 320 CSS px).
- Uses actual screen short-side metrics when available.
- Forces five single-row cards.
- All meaningful content fits inside the first 320 px.
- No horizontal scrolling.

Desktop behaviour:
- Keeps the original five-card layout.
