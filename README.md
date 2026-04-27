# Miki Golf

Static Netlify site for the public Miki Golf performance dashboard.

## Update Flow

The site data is generated from the private Caddie tracker by:

```sh
python3 ../Scripts/update_miki_golf_site.py
```

To publish:

```sh
python3 ../Scripts/update_miki_golf_site.py --publish
```

The generated public data file is `data/miki-golf-data.js`.

Do not add GHIN credentials, email addresses, private household details, or source tracker files to this repository.
