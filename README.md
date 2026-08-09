# budyears-site

The public website for [budyears.com](https://budyears.com) — the landing page,
the Privacy Policy and the Terms of Use.

Separate from the app repository on purpose. The app is closed source; these
documents have to be reachable by anyone, without a login, because App Review
fetches the privacy policy URL and so does every regulator and parent who goes
looking for it.

## Structure

    index.md      landing page
    privacy.md    -> /privacy
    terms.md      -> /terms
    _layouts/     one HTML layout, no theme, no plugins, no CDN
    CNAME         custom domain

## These are the published versions

Editing a document here changes what users are bound by. There is deliberately
no second copy in the app repository — two copies of a privacy policy drift,
and the published one is the one that counts.

## Before the app is published

- [ ] **A `/get` link that sends a phone to the right store.** One URL to put
      in a message, a QR code, or a class handout, which reads the
      `User-Agent` and redirects: iOS and iPadOS to the App Store, Android to
      Play, anything else to a page showing both.

      Client-side is enough — this site is Jekyll on GitHub Pages with no
      server to run logic on — so a small script in a static page, with the
      two badges rendered underneath as the no-JavaScript fallback. That
      fallback is the part worth getting right: a redirect that fails silently
      leaves someone on a blank page with no way to the app.

      Not Apple Universal Links or Android App Links, which are a different
      mechanism: those open an *already installed* app from a web URL and need
      `apple-app-site-association` and `assetlinks.json` served from this
      domain. Worth doing later so a shared link opens the app rather than the
      site, but it solves a different problem and needs the app's team and
      bundle identifiers, which only exist once the app is registered.
