# Turntable (web)

A landscape now-playing display for Spotify: album sleeve on the left, a
translucent record turning beside it, tonearm on the right.

Open it on a phone, sign in once, and add it to the home screen. It runs
entirely in the browser — there is no server, and your Spotify token is kept
in that browser's own storage and nowhere else.

Reading playback state and using the transport controls both require Spotify
Premium; that is Spotify's rule, not this page's.

## Setup

1. Create an app at [developer.spotify.com/dashboard](https://developer.spotify.com/dashboard).
2. Add this page's own URL as the Redirect URI, exactly.
3. Tick **Web API**, save, and paste the Client ID into the page.

## Why this exists

The better version of this is a native Android app that reads the phone's
media session directly — no account, no API, works with any player. This web
version is the fallback for when that is not an option.
