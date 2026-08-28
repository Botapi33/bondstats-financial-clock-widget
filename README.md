# BondStats Global Financial Clock Widget v6

This build uses a mobile-first fail-safe architecture for Google Sites.

## Why this fixes the previous issue
Mobile is the default layout. Desktop is only enabled when ALL of these are true:
- hover is available
- pointer is fine
- maxTouchPoints is zero
- physical/visual screen width is at least 900px
- user agent is not mobile

Therefore an oversized Google Sites iframe cannot accidentally trigger the desktop five-column layout on a phone.

The mobile widget is also capped to a safe physical width derived from screen/visualViewport and aligned to the left.

Includes Tokyo, Singapore, Hong Kong, London and New York.
