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
