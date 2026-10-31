Version v1.1: Compact, equal-width Date and Time fields in Edit Journey dialog (iPhone-friendly).

App version: v1.0 (initial numbered release).
Future updates should increment the displayed version in index.html and the service-worker cache revision.

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

Update v18: Removed Visual Journey Summary explanatory text. Save Photo uses native file sharing (iOS Share Sheet > Save Image) where available; falls back to PNG download. Browser cannot silently write to Photos.

Version 18: Design B map-and-transport visual summary, generated from saved journeys and selected period. Save Photo and other app features retained.

Version 19: Rebuilt Visual Journey Summary image as precise aligned Design B, with map route, transport icons, 3 KPI tiles, doughnut legend and monthly bars. Existing data, Save Photo and eye toggles retained.

Backup & Restore: Export JSON to Files/iCloud Drive, import with merge or replace, and monthly in-app reminder. The last-backup date is updated only after user confirmation.

Update: Five bottom tabs (Home, History, Statistics, Visual Summary, Settings). Backup and restore now live in Settings. Existing journey data is preserved.

Update: Distinct dark-green navigation buttons and refined SVG icons for Home, History, Statistics, Visual Summary, and Settings.

Navigation refinement: restored neutral white bottom navigation and subtle gray active tab; improved SVG icons retained.

Update: compact neutral bottom navigation with smaller buttons and icons; labels and other features unchanged.

Destination shortcut buttons now dismiss the on-screen keyboard immediately.

Update: Edit existing journeys from History and Last 3 Journeys on Home. Edit transport, destination, date, time and optional price.

Fix: Edit dialog is initialized before JavaScript; Save Journey works again. Delete buttons appear beside Edit in Home and History. Failed saves/deletes roll back in memory.

Version 1.2: Edit Journey dialog no longer automatically opens Transport selector; mechanical counter digits vertically centered.

Version 1.3: Settings Emergency Button with four categories and 10 original rotating messages each (40 total).

Version 1.4: centered mechanical counter numerals, 150 emergency messages across five categories, larger square red emergency button.

Version 1.5: Added sixth Emergency Button category, Platform Fortune Teller, with 30 original messages (180 total).

Version 1.7: Destination input briefly pulses green twice after a journey is successfully saved; keyboard remains dismissed.

Version 1.8: Destination field confirms successful saves with one slow green border flash and a faint upper-right check mark. No field background flash or scaling.

Version 1.9: stronger single green border flash and bright green check, synchronized to appear and disappear together.
