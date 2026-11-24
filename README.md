# Hugo

Example [Hugo](https://gohugo.io/) static site. Hugo is a fast static site generator written in Go.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Static site — Railpack build |
| Single-page application (SPA) | off |
| Project directory | `/` |
| Output directory | `/public` |
| Install command | leave empty |
| Build command | leave empty |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# run in development mode
hugo server

# build for production
hugo --minify
```

Requires [Hugo](https://gohugo.io/installation/) 0.169 or later.
