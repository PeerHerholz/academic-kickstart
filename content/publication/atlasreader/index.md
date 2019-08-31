+++
title = "AtlasReader: A Python package to generate coordinate tables, region labels, and informative figures from statistical MRI images"
date = 2019-02-24T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Michael Notter", "Dan Gale", "Peer Herholz", "Ross Markello", "Marie-Laure Notter-Bielser", "Kirstie Whitaker"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Notter et al., (2019). AtlasReader: A Python package to generate coordinate tables, region labels, and informative figures from statistical MRI images. Journal of Open Source Software, 4(34), 1257, https://doi.org/10.21105/joss.01257"
#publication_short = "In *STC*"

# Abstract.
abstract = "A major advantage of magnetic resonance imaging (MRI) over other neuroimaging methods is its capability to noninvasively locate a region of interest (ROI) in the human brain. For example, using functional MRI, we are able to pinpoint where in the brain a cognitive task elicits higher activation relative to a control. But just knowing the Cartesian coordinate of such a ROI is not useful if we cannot assign it a neuroanatomical label. For this reason, MRI images are usually normalized into a common template space (Fonov et al., 2011), where well-established atlases can be used to associate a given coordinate with the label of a brain region. Most major neuroimaging software packages provide some functionality to locate the main peaks of an ROI but this functionality is often restricted to a few atlases, frequently requires manual intervention, does not give the user much flexibility in the output creation process, and never considers the full extent of the ROI. To tackle those shortcomings, we created AtlasReader, a Python interface for generating coordinate tables and region labels from statistical MRI images. With AtlasReader, users can use any of the freely and publicly available neuroimaging atlases, without any restrictionto their preferred software package, to create publication-ready output figures and tables that contain relevant information about the peaks and clusters extent of each ROI. To our knowledge, providing atlas information about the full extent of a cluster, i.e. over which atlas regions does a ROI extent, is a new feature that is not available in any other, comparable neuroimaging software package."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.21105/joss.01257"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
#tags = ["Source Themes"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["methods"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "example"

# Links (optional).
url_pdf = "https://www.theoj.org/joss-papers/joss.01257/10.21105.joss.01257.pdf"
url_code = "https://github.com/miykael/atlasreader"
url_dataset = ""
url_project = "https://zenodo.org/record/2575731#.XK3lSZMzaV4"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
