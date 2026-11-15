# Nivo AI website

Jekyll site for Nivo AI, hosted on GitHub Pages.

## Structure

| Path | Purpose |
| --- | --- |
| `_config.yml` | Site settings, contact email, base URL |
| `_data/` | Navigation, principles and steps shown on the home page |
| `_layouts/` | `default` page shell and `doc` layout for legal pages |
| `_includes/` | `head`, `header`, `footer` |
| `_sass/` | Styles split by concern, compiled through `assets/css/main.scss` |
| `_pages/` | Home, privacy policy, terms |

## Run locally

```bash
bundle install
./run_server.sh
```

## Deploy

Push to `main`, then in the repo go to Settings, Pages, and select Deploy from a branch, `main`, `/ (root)`.
If you use a custom domain, set `baseurl` to `""` and `url` to the domain in `_config.yml`.
