# Development and maintenance

## Run locally

From the repository root, run `python3 -m http.server 5500`, then open [localhost:5500](http://localhost:5500). Python 3 is only a development-server option; VS Code Live Server also works. Stop the server with Ctrl+C. No package installation or build is required to serve this checkout.

## Implementation and boundaries

A static editorial tribute to Norman Borlaug with a portrait, timeline, quotation, and external reference. There is no application storage or backend.

## Make changes

Edit biography, dates, quotation attribution, and reference links in `index.html`; edit the editorial grid and image cropping in `styles.css`.

## Source map

- [`index.html`](../index.html)
- [`styles.css`](../styles.css)

## Verification

No automated test command is provided by this repository. The following manual checks are a checklist, not a claim that browser QA has been completed.

1. Check the portrait caption and timeline alignment across screen sizes.
2. Follow the reference link and inspect the page at 200% zoom.
3. Inspect the browser console and Network panel for missing assets or script errors; check keyboard access, phone width, and 200% zoom.

## Deployment

Serve the tracked HTML, CSS, JavaScript, and required assets from a static host, preserving relative paths and filename case. There is no application server or environment-variable configuration in this checkout. Verify the actual deployment URL, external resources, and the checks below after publishing. A repository existing on GitHub does not by itself prove Pages is enabled.

## Keep documentation current

Update the README and this guide when entry points, dependencies, behavior, or deployment steps change. Record commands actually run and distinguish them from pending manual checks.
