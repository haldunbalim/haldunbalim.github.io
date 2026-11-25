[My Website](https://haldunbalim.github.io)

## Editing

| What | File |
|------|------|
| Name, photo, contact links | `_data/profile.yml` |
| Bio | `_includes/bio.md` |
| News | `_data/news.yml` |
| Papers | `_data/publications.yml` (thumbnails in `assets/img/pubs/`, video clips + posters in `assets/media/<paper>/`) |
| Co-author homepages | `_data/people.yml` |

## Local preview

```
mamba run -p ~/venvs/jekyll jekyll serve --livereload    # http://localhost:4000
```

From a laptop: `ssh -L 4000:localhost:4000 <server>` first.
