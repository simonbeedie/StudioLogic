# StudioLogic

A static site of ICT, Computing and Media Studies teaching resources for students
(initially Years 7–13, UK curriculum). Hosted on GitHub Pages, and intended to be
embedded page-by-page as iframes inside the Firefly VLE.

## Structure

The site is subject-first: Computer Science and Media Studies each contain their
own GCSE and A-Level year folders. KS3 is separate, covering Years 7–9.

```
/
├── index.html                  # Homepage
├── assets/
│   ├── css/                    # Shared stylesheet(s)
│   └── images/
├── ks3/
│   ├── year-7/
│   ├── year-8/
│   └── year-9/
├── computer-science/
│   ├── gcse/
│   │   ├── year-10/
│   │   └── year-11/
│   └── a-level/
│       ├── year-12/
│       └── year-13/
└── media-studies/
    ├── gcse/
    │   ├── year-10/
    │   └── year-11/
    └── a-level/
        ├── theory/              # Theory reference pages (media language,
        │                        # representation, industries, audiences).
        │                        # Linked to directly from students' work,
        │                        # so filenames here are stable once published.
        ├── year-12/
        └── year-13/
```

All file and folder names are lowercase and hyphenated (no spaces or capitals),
since they form part of the site's URLs.

## Deployment

This is a static site with no build step. To make it live, enable **GitHub Pages**
manually in this repo's **Settings → Pages**.
