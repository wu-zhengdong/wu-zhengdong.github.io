# wu-zhengdong.github.io

Personal academic website of Zhengdong Wu, built with [al-folio](https://github.com/alshedivat/al-folio) v1.x and deployed to GitHub Pages.

## Where things live

| What                 | File                                        |
| -------------------- | ------------------------------------------- |
| Site name, URL, SEO  | `_config.yml`                               |
| Home page bio        | `_pages/about.md`                           |
| Profile photo        | `assets/img/prof_pic.jpg`                   |
| Publications         | `_bibliography/papers.bib`                  |
| Journal badge colors | `_data/venues.yml`                          |
| News                 | `_news/*.md`                                |
| Projects             | `_projects/*.md`                            |
| Email / social links | `_data/socials.yml`                         |
| Blog (hidden)        | `_posts/`, enable `nav` in `_pages/blog.md` |

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Deploy

Pushing to `main` runs `.github/workflows/deploy.yml`, which builds the site into the `gh-pages` branch. In the repository settings, set **Actions → General → Workflow permissions** to _Read and write_, and **Pages → Source** to the `gh-pages` branch.
