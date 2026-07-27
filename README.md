# meal-plan-calendar

A public iCalendar (`.ics`) feed for one household's weekly dinner plan, published so a [Skylight Calendar](https://myskylight.com/) can subscribe to it (My Skylight app → Synced Calendars → Sync new calendar → Calendar URL).

`meals.ics` is generated and pushed automatically by a local Claude Code skill after each week's grocery order is confirmed. Only a dish name and a one-line description per day ever go into the feed — no addresses, no account details, no shopping list, no personal information of any kind.

This repo is public only because Skylight's calendar-subscribe feature requires a URL it can fetch without logging in. Nothing here links to any private repository, service, or account.
