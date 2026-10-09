# frankie137.github.io

Source for my personal homepage, live at **https://frankie137.github.io**.

Built on [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) (MIT, see [LICENSE](LICENSE)) and served by GitHub Pages.

## Editing

- Page content: [`_pages/about.md`](_pages/about.md)
- Name, bio, avatar, and links: [`_config.yml`](_config.yml)
- Top navigation: [`_data/navigation.yml`](_data/navigation.yml)
- Paper teaser images: [`images/`](images/)

## Local preview

```bash
bundle install
bash run_server.sh   # http://127.0.0.1:4000
```

## Google Scholar citations (optional)

1. Add a repository secret `GOOGLE_SCHOLAR_ID` (Settings → Secrets and variables → Actions). Its value is the `user=` part of your Scholar profile URL.
2. Set `googlescholar` in `_config.yml`.
3. The **Get Citation Data** workflow will then push citation counts to the `google-scholar-stats` branch every day. Until the secret exists, the workflow skips every step.
