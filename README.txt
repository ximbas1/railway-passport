Railway Passport — Updated version (October 2026)

Changes:
- Quick destination buttons: Kundl, Wörgl, Innsbruck (fill field without saving).
- Monthly ride bar chart after journey history, showing counts and destinations.
- Preserves existing localStorage key railway-passport-v1 so existing rides remain.

GitHub Pages update:
1. Open your railway-passport GitHub repository.
2. Upload all six files from this ZIP into the repository ROOT, replacing existing files.
3. Commit the changes.
4. Reload the site. If the previous version remains, close/reopen the app or refresh again; service worker cache is updated.

Your ride data stays in the browser where it was recorded. Do not clear website data.

Colorful Alpine icon update: upload all six files. If the old home-screen icon persists, remove and re-add the shortcut.

Version 4: Added Car as a third transport choice next to Train and Bus. Previous journeys remain stored under railway-passport-v1.

Layout update: Train, Bus, and Car buttons now fit on one row on narrow phone screens.

Version 6: Forced three equal-width transport buttons on one row. Service worker now fetches fresh HTML on navigation. If old layout persists, reload site in browser before reopening Home Screen shortcut.

Version 7: App renamed Public Transport Counter. Header subtitle: My journeys - by Dr. Aguiar, Mario. Existing saved journeys retained.

Version 8: Four transport buttons (Train, Bus, Car, Vespa) in one row. Editable train ticket prices for Kundl, Woergl, Innsbruck and monthly train ticket totals. Prices stored separately; existing journey storage preserved.

Update: compact scrollable journey history (260px max height), monthly breakdown by destination and transport with ride counts and train ticket costs. Car/Bus/Vespa show dash because no prices are configured for them. Local journey data unchanged.

Version 11: Four compact always-labelled doughnut statistics (month/year/all), ticket spending in EUR; prompts for train fare when a destination has no saved price. Journey history remains in localStorage railway-passport-v1.

Version 12: statistics eye hide/show with persistent visibility, month and year selectors and All Time checkbox, four compact labeled doughnut charts, and automatic Smart Journey Summary. Ticket spending covers train rides only. Local journey history preserved.

Version 13: Journey total card now features a compact illustrated city street map, A-to-B route and manual mechanical counter. The miniature counter updates with total journeys. No GPS or network maps used.

Version 14: Counter map redesigned with person, dynamic mechanical counter, branching routes to four color-coded transport choices. New approved map/counter/transport app icons. Existing local journey storage and statistics preserved.

Version 15: Clean counter: large dynamic mechanical tally on left, no Journeys recorded caption; minimal map with A-B dotted route and all four transport icons on right.

Version 16: Separate persistent eye controls for Journey History and Journeys by Month; auto-updating canvas Visual Journey Summary below Smart Journey Summary with Save PNG. Statistics use selected month/year or All Time. No external services.
