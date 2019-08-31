+++
# Project title.
title = "Structure & function of the auditory system"

# Date this page was created.
date = 2019-04-10T00:00:00

# Project summary to display on homepage.
summary = "How is the auditory system organized in the human brain?"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["auditory system"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/peerherholz"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
[image]
  # Caption (optional)
  #caption = "Photo by rawpixel on Unsplash"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
Glasser at al. summarized it quite well in their 2016 "A Multi-modal Parcellation of Human Cerebral Cortex" paper when they were stating "In contrast to early visual and somatomotor cortex, parcellation of the early auditory cortex has proven much more challenging..." (Suppl. 3, page 35, line 7-8 ). The robust and reliable localization and parcellation of the human auditory cortex, along with it's functional principles has been the subject of a long-standing debatte with the vast amount of possible analyses that to can be applied to the variety of possible measurements adding yet another layer of complexity. Based on that I started developing ALPACA (OSF page here), an open-source python toolbox for the "Automated Localization and Parcellation of Auditory Cortex Areas" (full disclosure: I had the abbreviation first and then tried to come up with a fitting name, luckily that worked out pretty well) which will include experiment and analyses scripts for different paradigms (natural sounds & classic tone bursts) and approaches (structural parcellation, mapping of auditory ROIs from atlases, fMRI, EEG, searchlights, encoding, etc.). The respective parts can be combined as preferred and run as functions or fully automated via docker and/or as a BIDS app, hopefully helping folks with creating ROIs for their study and/or further advancing the investigation of the human auditory cortex.
