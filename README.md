# Instagram Unfollower Tracker

A browser-side tool for comparing Instagram accounts you follow with accounts that follow you back. The interface includes filtering, search, whitelist management, and local result/timing storage.

## How it works

The current implementation is a bundled JavaScript application intended to run on Instagram's website while you are signed in. It reads the account data available to the logged-in browser session and displays the comparison in an injected interface.

## Run it

1. Open [Instagram](https://www.instagram.com/) in a desktop browser and sign in.
2. Open the browser's Developer Tools and select the Console.
3. Open `tracker.js` from this repository and copy its contents.
4. Paste the script into the Console and run it.
5. Use the tracker interface that appears on the page.

Only run browser-console code that you have reviewed and trust. The script runs in the context of your Instagram page and can access the page session.

## Included interface

- Compare accounts you follow with your followers.
- Filter and search the displayed results.
- Manage a whitelist and import or export whitelist data.
- Keep selected settings and results in browser `localStorage`.

The tool is not affiliated with or endorsed by Instagram. Instagram may change its website or private endpoints, which can cause the tracker to stop working.

## Privacy and limitations

- This repository contains a browser-side script; it does not provide a hosted service or account-recovery feature.
- The current implementation stores whitelist and timing data in the browser's local storage.
- Do not share your Instagram password, session cookies, or private account exports.
- Use the tool responsibly and follow Instagram's terms and rate limits. Repeated or automated requests may be restricted by Instagram.

## Files

- `tracker.js` — the existing bundled application script.
- `LICENSE` — project license.

---

Maintained by [Shivam Raghuvanshi](https://github.com/ShivamRaghuvanshi2006).
