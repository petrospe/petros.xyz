# petros.xyz

A static personal landing page for Peter Petropoulos, published at [petros.xyz](https://petros.xyz). The site has no build step or package manager configuration.

## Pages and files

- `index.html` is the main landing page, with links to the portfolio and social profiles. Its moon icon points to `me.petros.xyz` on days 1–15 of each month and to an IPFS-hosted page from day 16 through month-end, based on the visitor's local date.
- `style.css` contains the landing page styles.
- `under-construction.html` is a separate placeholder page linked from the email icon.
- `CNAME` configures the custom domain `petros.xyz` for static hosting that supports CNAME files, such as GitHub Pages.

## Preview locally

Open `index.html` in a browser, or serve the repository directory with Python:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

The pages load some fonts, icons, animation styles, and particles.js from external CDNs, so those resources require an internet connection.
