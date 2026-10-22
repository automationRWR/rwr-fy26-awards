# RWR email signature assets

Public image host for the RWR Group email signatures (JobAdder and others).

## Logos
Base URL: `https://raw.githubusercontent.com/automationRWR/rwr-fy26-awards/main/email-signatures/logos/`

| File | Size (2x) | Shows at |
|---|---|---|
| rwr-group.png | 140 × 68 | 70 × 34 |
| retailworld.png | 172 × 71 | 86 wide |
| hospoworld.png | 172 × 70 | 86 wide |
| rwr-health.png | 180 × 54 | 90 wide |
| rwr-construction.png | 160 × 71 | 80 wide |
| powered-by-people.png | 124 × 72 | 62 wide |

## Staff photos
Folder: `email-signatures/photos/`

- One round 128 × 128 PNG per person on a white background.
- Named FirstName-LastName exactly as in JobAdder (same capitals and spaces), e.g. `Liam-Turner.png`.
- The signatures load `photos/{Consultant.FirstName}-{Consultant.LastName}.png`. JobAdder turns {Consultant.Email} into a full link, so it can't be used in an image address.
- Everyone using a photo signature needs a file here, or their signature shows a broken image.

## JobAdder signatures
`jobadder/` holds one HTML file per brand, ready to paste into JobAdder's HTML/source view.
Still to swap before use: `{AGENCY_FINDER_URL}` (brands) and `{UNSUBSCRIBE_EMAIL}` (all but Retailworld).
