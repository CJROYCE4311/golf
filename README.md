# Royce Golf

Static Netlify site for the public Royce Golf dashboards.

- `index.html` is the landing page.
- `miki.html` is Miki's dashboard.
- `chris.html` is Chris's dashboard.

## Update Flow

The site data is generated from the private Caddie trackers by:

```sh
python3 ../Scripts/update_miki_golf_site.py
```

To publish:

```sh
python3 ../Scripts/update_miki_golf_site.py --publish
```

The generated public data files are:

- `data/miki-golf-data.js`
- `data/chris-golf-data.js`

Do not add GHIN credentials, email addresses, private household details, or source tracker files to this repository.
