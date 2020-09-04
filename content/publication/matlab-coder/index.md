---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Getting the most from MATLAB: ditching canned routines and embracing coder"
authors: 
- admin
- John Gibson
date: 2019-10-28T13:52:20-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-10-28T13:52:20-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Economics Bulletin"
publication_short: ""

abstract: "This paper demonstrates the efficiency gains that can be realized by replacing canned routine calls within MATLAB with user-generated versions that simplify the underlying computations. Once canned routines have been replaced, we integrate C++ executables (or MEX files) using MATLAB's Coder to automatically convert our MATLAB code. We demonstrate these efficiency gains by computing the stationary equilibria and associated transition path for an economy with incomplete insurance markets following a change in government debt policy. The combined process of replacing calls to canned routines and integrating MEX files reduces our runtime from just over 24 hours to approximately 16 minutes."

# Summary. An optional shortened abstract.
summary: ""

tags: 
- MATLAB
- C++
- MATLAB Coder
- Incomplete Markets
- Stationary Distribution
- Transitional Dynamics
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://www.accessecon.com/Pubs/EB/2016/Volume36/EB-16-V36-I4-P243.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
