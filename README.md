# AD-Genomics-Cardiff Team Site

This repository contains the **Quarto source** for the AD-Genomics-Cardiff team
website. It is intended to serve as a lightweight team hub for Alzheimer’s
disease research at UK DRI Cardiff, with space for projects, outputs, people,
and shared resources.

---

## What this site is for

The site is structured to support:
- a **team landing page**
- a **projects/workstreams page**
- an **outputs page** for papers, software, data, and presentations
- a **people page**
- a **resources page** for repositories, methods, and practical links

It keeps the original Quarto/GitHub Pages setup, but
the content model is now team-focused for AD-Genomics-Cardiff.

---

## Structure of the site

The site currently includes five main pages:

- **Home** (`index.qmd`)  
  Team overview, research themes, and quick links.

- **Projects** (`pages/projects.qmd`)  
  Team workstreams and current analysis areas.

- **Outputs** (`pages/outputs.qmd`)  
  Publications, talks, software, datasets, and related outputs.

- **People** (`pages/resume.qmd`)  
  Team members, roles, and collaboration information.

- **Resources** (`pages/cv.qmd`)  
  Repositories, methods, data resources, and contact links.

Some pages still contain clearly marked placeholders and should be updated with
confirmed team details over time.

---

## Editing the site

Common files to update:

- [ ] **`_quarto.yml`**: site title, navbar labels, and external links
- [ ] **`index.qmd`**: homepage overview and research themes
- [ ] **`pages/projects.qmd`**: active projects or workstreams
- [ ] **`pages/outputs.qmd`**: publications, software, datasets, talks, and reports
- [ ] **`pages/resume.qmd`**: people and team information
- [ ] **`pages/cv.qmd`**: resources, repositories, and contact details
- [ ] **`_partials/links.qmd`**: shared team links
- [ ] **`assets/images/profile.png`**: replace with a team image or research banner if desired

## Publish with GitHub Pages
This repository is configured to publish automatically using **GitHub Actions**.

To enable publishing:
1. Go to **Settings → Pages**
2. Under *Build and deployment*, set **Source** to **GitHub Actions**
3. Save

Your site will be published at:

```
https://<your-username>.github.io/<repository-name>/
```

---

## Local preview (optional)

If you have Quarto installed, you can preview the site locally:

```bash
quarto preview
```

Before pushing changes, it’s good practice to run:

```bash
quarto render
```

---

## Design & customisation

* The site uses a Bootstrap-based Quarto theme
* UK DRI colours are defined in `styles.css`
* Navigation is defined in `_quarto.yml`
* The current pass keeps filenames stable for minimal disruption, even where page purpose has changed

The site can remain lightweight or be expanded later with dedicated people,
methods, publications, or collaboration pages.

---

## License

This material is licensed under a
**Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** license.

You are free to reuse and adapt this site material, provided you:

* give appropriate credit
* indicate if changes were made
* share derivative works under the same license
