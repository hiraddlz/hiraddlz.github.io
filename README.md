# hiraddlz.github.io

Personal site of Hirad Dolatzadeh | Machine Learning Engineer / Data Scientist.
Live at **https://hiraddlz.github.io**.

## Editing content

- **Home page** (`/`): everything on it (roles, stats, experience, projects, skills, education,
  certifications) comes from [`_data/profile.yml`](_data/profile.yml). Edit that file; the layout
  in [`_layouts/home.html`](_layouts/home.html) renders it.
- **Résumé / CV** (`/cv/`): [`_pages/cv.md`](_pages/cv.md).
- **Portfolio, publications, teaching**: the `_portfolio/`, `_publications/`, `_teaching/` collections.
- **Photo**: `images/profile-web.jpg` (640×640) is used on the home page; `images/profile.png` is the original.

## Running locally

```bash
bundle install
bundle exec jekyll serve -l
```

Built on Jekyll / GitHub Pages (forked from the Academic Pages template).
