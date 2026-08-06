# How to edit the site

Everything you can change lives in ONE place: near the top of `index.html`,
in the block that starts with `const CONTENT = {`.

## To make a change
1. Go to the repository on github.com and click `index.html`.
2. Click the pencil icon (top right of the file view).
3. Find the line you want — rates, phone number, any paragraph of text.
4. Change the words BETWEEN the quote marks. Don't remove quotes or commas.
5. Scroll down, click **Commit changes**.
6. The live site updates itself in about a minute. Refresh to see it.

## Examples
Change the monthly rate:
    { period: "Monthly", price: "$6,250", ... }
becomes
    { period: "Monthly", price: "$6,500", ... }

Change the phone number: edit BOTH lines —
    phone:     "(310) 770-7059",
    phoneHref: "+13107707059"

## Swapping a photo
Photos live in the `images` folder with fixed names (hero.jpg, living.jpg,
kitchen.jpg, bedroom.jpg, office.jpg, bath.jpg, balcony-day.jpg,
balcony-night.jpg, balcony-egg.jpg, skyline-night.jpg, pool-night.jpg,
game-room.jpg, lounge.jpg, walk-living.jpg, walk-dining.jpg,
walk-kitchen.jpg, og.jpg). To replace one, upload a new photo
with the exact same name into `images` (GitHub: Add file → Upload files).
Keep photos under ~400 KB so the page stays fast.

## If something breaks
Every change is saved in the History tab — open the file's History,
find the last good version, and restore it. Nothing is ever lost.
