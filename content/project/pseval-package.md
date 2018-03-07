+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "pseval"

# Project summary to display on homepage.
summary = "Methods for Evaluating Principal Surrogates of Treatment Response"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "pseval.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["surrogates"]

# Optional external URL for project (replaces project detail page).
external_link = "https://sachsmc.github.io/pseval"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
Contains the core methods for the evaluation of principal surrogates in a single clinical trial. Provides a flexible interface for defining models for the risk given treatment and the surrogate, the models for integration over the missing counterfactual surrogate responses, and the estimation methods. Estimated maximum likelihood and pseudo-score can be used for estimation, and the bootstrap for inference. A variety of post-estimation summary methods are provided, including print, summary, plot, and testing.
