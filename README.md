# BSSw PSIP GitHub Page

The [Better Scientific Software PSIP site](https://bssw-psip.github.io/) (bssw-psip)
is the main landing page that allows users a central portal to access guides,
project tracking cards, and recent posts about the Productivity and
Sustainability Improvement Planning (PSIP) process.

Though the content available in this portal, the user can explore the purposes
and procedures to enable use of the PSIP process for their project.

This application is built using GitHub Pages on top of the suggested Jekyll
theme.

## Structure

This site is currently structured into three sites:

- _Main Site_: This is the main site/home page. The source code can be found at https://github.com/bssw-psip/bssw-psip.github.io
- _Practice Guides_: This subsite provides the guides for utilizing PSIP to improve team practices. The source code can be found at https://github.com/bssw-psip/practice-guides
- _Project Tracking Card Catalog_: This subsite provides previously developed and example PTCs, for use in tracking improvement progress. The source code can be found at https://github.com/bssw-psip/ptc-catalog

## Locally Testing the Site

Because BSSw PSIP is powered through GitHub Pages, there are extensive tutorials
in existence on how to build and test sites locally.

See the main [GitHub Pages documentation](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll).

**NOTE**: If you are a developer on a Mac and using Ruby 3, please add the
following line to the `Gemfile` before running `bundle install`:
```
gem "webrick"
```
This is a well-documented workaround to a [known bug](https://github.com/jekyll/jekyll/issues/8523).

## Acknowledgements

The development of this site was supported by the Exascale Computing Project
(17-SC-20-SC), a collaborative effort of the U.S. Department of Energy
Office of Science and the National Nuclear Security Administration.
