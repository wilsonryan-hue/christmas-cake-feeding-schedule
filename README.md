# Free Christmas cake and pudding feeding schedule generator (one HTML file, nothing stored)

Pick the day you bake your Christmas cake and make your pudding, how often you feed (weekly or fortnightly) and the day you ice. You get a dated, printable list: bake, each feed, the last feed, marzipan, icing, and steaming the pudding on Christmas Day. Stir-up Sunday (the last Sunday before Advent) is worked out for you. No sign-up, no server, no cookies, no build step: it is one `index.html` file.

**Use it now, no install:** download `index.html` and open it in any browser, or use the page version with FAQs at [tchworks.co.uk/free/stir-up-sunday-2026-christmas-cake-pudding-schedule](https://www.tchworks.co.uk/free/stir-up-sunday-2026-christmas-cake-pudding-schedule/?utm_source=github&utm_medium=repo&utm_campaign=cake-schedule-repo).

**Free printable PDF (no install):** [Download the A4 pack](https://github.com/wilsonryan-hue/christmas-cake-feeding-schedule/releases/download/v1.0.0-free-printable/christmas-cake-pudding-schedule-2026-free.pdf) — Stir-up Sunday 2026 weekly + fortnightly + alcohol-free pudding schedules, plus a blank custom sheet ([release notes](https://github.com/wilsonryan-hue/christmas-cake-feeding-schedule/releases/tag/v1.0.0-free-printable)).

## The rules it uses

- Stir-up Sunday is the Sunday before Advent Sunday; Advent Sunday is the Sunday nearest 30 November. The page shows the dates for the current Christmas (21 Nov 2027, 26 Nov 2028 and so on follow the same rule).
- Feed with 1 to 2 tablespoons of brandy, rum, sherry or fruit juice, weekly or fortnightly.
- Stop feeding the cake 6 days before marzipan, so the top dries (our suggestion).
- Marzipan 2 days before icing (our suggestion).
- Stop feeding the pudding on 18 December (our suggestion).
- Christmas Day: steam the pudding at least 2 hours, until 70C in the centre, reheat once only.

Worked example for 2026 (defaults): bake and pudding on Sun 22 Nov, weekly feeds on 29 Nov, 6 Dec and 13 Dec (last), marzipan Sat 19 Dec, icing Mon 21 Dec, steam on Fri 25 Dec.

## Change it

Open `index.html` in a text editor. The gap rules are in the `run()` function (`add(marz,-6)`, `add(iceD,-2)`, `new Date(Y,11,18)`).

## Limits

Sensible defaults, not a recipe: follow your own recipe where it differs. An alcohol-free pudding has no spirit to preserve it, so use it within about four to six weeks or freeze it.

## Licence

MIT. Made by [TCH Works](https://www.tchworks.co.uk/?utm_source=github&utm_medium=repo&utm_campaign=cake-schedule-repo), which also publishes free [Advent calendar activities](https://www.tchworks.co.uk/free/advent-calendar-activities-2026/?utm_source=github&utm_medium=repo&utm_campaign=cake-schedule-repo), [more free Christmas tools](https://www.tchworks.co.uk/free/?utm_source=github&utm_medium=repo&utm_campaign=cake-schedule-repo), [Christmas cards](https://www.tchworks.co.uk/cards/christmas/?utm_source=github&utm_medium=repo&utm_campaign=cake-schedule-repo) and a printable [Christmas Budget & Gift Planner](https://tchworks.gumroad.com/l/kazjns?utm_source=github&utm_medium=repo&utm_campaign=cake-schedule-repo).

## Also on Gumroad

Get the same free PDF with instant download on Gumroad: https://tchworks.gumroad.com/l/utinki
