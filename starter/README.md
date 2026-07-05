# Demo card images

Drop card photos here to populate the static demo (card grid, detail drawer, and
the 3D Showcase). File naming must match the seeded card IDs in
[`src/lib/seed.ts`](../../src/lib/seed.ts):

```
public/starter/<cardId>/front.jpg
public/starter/<cardId>/back.jpg
```

Seeded card IDs:

| Card | Front | Back |
| --- | --- | --- |
| Michael Jordan 1986 Fleer | `card_seed_jordan86/front.jpg` | `card_seed_jordan86/back.jpg` |
| Luka Doncic 2018 Prizm | `card_seed_luka18/front.jpg` | `card_seed_luka18/back.jpg` |
| Mike Trout 2011 Topps Update | `card_seed_trout11/front.jpg` | `card_seed_trout11/back.jpg` |
| Patrick Mahomes 2017 Prizm | `card_seed_mahomes17/front.jpg` | `card_seed_mahomes17/back.jpg` |
| LeBron James 2003 Topps Chrome | `card_seed_lebron03/front.jpg` | `card_seed_lebron03/back.jpg` |
| Ronald Acuna Jr. 2018 Topps Chrome | `card_seed_acuna18/front.jpg` | `card_seed_acuna18/back.jpg` |

Notes:
- Use `.jpg` (the seed paths reference `.jpg`). Portrait ~3:4 works best.
- Until a file exists, the card shows an initials placeholder and the Showcase
  shows the procedural slab — no errors.
- These are served statically, base-path-adjusted for GitHub Pages.
