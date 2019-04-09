+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Research"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"

  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0

  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*



[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"

  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"

  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  

[advanced]
 # Custom CSS.
 css_style = ""

 # CSS class.
 css_class = ""
+++
**music perception** </br>
As music is as divers as mysterious to such an extent that it's hard or nearly impossible to actually define it, I'm interested how music processing, especially perception, is shaped, how it can be described and possibly explained. To hopefully shed some light on this rather overwhelming question I investigate how human and non-human brains perceive and represent different music genres and how these representations can be explained based on auditory/music features, as well as conceptual and computational models. To do so I apply a broad range of methods, ranging from imaging (MRI & EEG) to behavior to artificial neural networks furthermore including important factors such as development (culture & music preference) and plasticity (musical training). You can find more information about this line of my research on the projects github or OSF page.
Furthermore, I'm working, as a remote contributor, in Harvard's music lab in the amazing Natinal History of Song project.

**auditory processing** </br>
Our normal all day life is full of an ever changing and highly complex soundscape. How and during which time point during auditory perception those countless sound categories emerge in the cortical and subcortical auditory pathway is not only a very interesting, but also challenging question. For a quite a while I'm particulary fascinated by the cortical interaction of music, singing and language, which I investigate through combined MRI & EEG, anazlying subsequent data using different connectivity and machine learning approaches. Additionally, possible factors of influence such as musical training and handedness are an important part of this research question. The project's github and OSF pages provide more information.


**structure & function of the auditory cortex** </br>
Glasser at al. summarized it quite well in their 2016 "A Multi-modal Parcellation of Human Cerebral Cortex" paper when they were stating "In contrast to early visual and somatomotor cortex, parcellation of the early auditory cortex has proven much more challenging..." (Suppl. 3, page 35, line 7-8 ). The robust and reliable localization and parcellation of the human auditory cortex, along with it's functional principles has been the subject of a long-standing debatte with the vast amount of possible analyses that to can be applied to the variety of possible measurements adding yet another layer of complexity. Based on that I started developing ALPACA (OSF page here), an open-source python toolbox for the "Automated Localization and Parcellation of Auditory Cortex Areas" (full disclosure: I had the abbreviation first and then tried to come up with a fitting name, luckily that worked out pretty well) which will include experiment and analyses scripts for different paradigms (natural sounds & classic tone bursts) and approaches (structural parcellation, mapping of auditory ROIs from atlases, fMRI, EEG, searchlights, encoding, etc.). The respective parts can be combined as preferred and run as functions or fully automated via docker and/or as a BIDS app, hopefully helping folks with creating ROIs for their study and/or further advancing the investigation of the human auditory cortex.


**"disorders" of music processing** </br>
Given the importance and prominent role of music for the majortity of people out there, it's quite hard to imaging lacking the ability to actually process or enjoy music. However, for people affected by amusia or musical anhedonia this is reality. While the first have difficulties perceiving and/or producing melodies (pitch) or rhythms (or both) (if you're interested check this great in depth and comprehensive review by Isabelle Peretz), the latter show the incapacity of enjoying listening to music (great introduction, study and overview by Martínez-Molina et al.). Interestingly, upon a closer look these two show some sort of "double dissociation" in that people affected by amusica can and do enjoy music despite the aforementioned problems, whereas people affected by musical anhedonia have no difficulties in processing music (e.g. it's structure). Hence, I'm very interested in both investigating possible models of explanation combining multimodal data with connectivity measures and multivariate approaches.


**tools for auditory neuroscience** </br>
Fellow folks working in auditory neuroscience know the somewhat struggle that goes along with that line of research, especially within the realm of MRI: due to the nature of the stimulus experiments can be harder to implement, take way longer SNR is far from being good and whatnot (make sure to check Jonathan Peelle's amazing review on that topic). Hence, working on how experiments can be improved is (like usual) as much as important as actually doing them. Besides the already mentioned ALPACA toolbox, I'm therefore also very interested in improving settings for auditory neuroscience experiments. To this end, I'm e.g., working on MRI aqusition parameters and sequences (for example ISSS & multiband) and a small toolbox that allows audiometry measurements in the MRI environment (corresponding OSF page).


**neuroinformatics & methods** </br>
I was once told that one doesn't have to understand neuroscience methods and statistics in order to apply. While this is certainly true, it's also certainly bad. Starting with very little method & zero programming skills everything was kinda overwhelming but at the same time fascinating. The combination of math, physics, informatics and biology amazed me and the more I read and gained practical experience the more I wanted to understand. I'm especially insterested in data management and quality control, non-standard experimental setups (e.g., naturalistic stimulation) and acquisition schemes (e.g., multiband, MT), processing steps (e.g., ICA, detrending), image registration, multi-modal measurements & data integretation, as well as multivariate analyses approaches (e.g., machine learning, encoding models). Furthermore, I'm working on pipeline creation / automization and cloud / hpc computing, recently setting up my first own server system.


**open & reproducible (neuro)science** </br>
Starting with the lack of details in the methods section of papers I was reading to no chance of having a look at the data or code (or sometimes even the whole publication) created some sort of frustration I found it hard to cope with. Hence, I'm trying to open up my daily research worklfow as much as possible throughout all stages using a variety of tools (great resource on how to get started can be found here). Through the support during my time as an "open science fellow" I was able to initiate the Open Science Initiative University of Marburg, an university wide organization fostering open science principles for example via hackrooms and hackathons (e.g. brainhacks), workshops (e.g. here), as well as general assistance and support (e.g. here). Additionally, I'm working on integrating comparably new and less know tools like open knowledge maps & scholia into research workflows and how to use virtualization software like docker & singularity for hustle free reproducibility and generalizabillity.

<a  href="http://www.researchtransparency.org/links/">
  <img  src="http://www.researchtransparency.org/media/rt_logo_square.png" alt="open science transperacy">
</a>
<small><sub> Nice badge, eh? Why not check out <a href="http://www.researchtransparency.org" target="_blank">http://www.researchtransparency.org</a> and commit to research transparency as well?</sub></small>
