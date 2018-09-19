+++
date = 2017-01-01T00:00:00  # Schedule page publish date.

title = "Modeling time to event data"
time_start = 2018-09-19T10:00:00
time_end = 2018-09-19T11:30:00
abstract = ""
abstract_short = ""
event = "KEP Methods Club"
#event_url = "https://example.org"
location = "Stockholm, Sweden"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["repro-resea"]

# Links (optional).
url_pdf = ""
url_slides = "https://sachsmc.github.io/Talks/kep-methods-survival"
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

[Andersen 2002, Multistate Models](Andersen-2002-multistate.pdf)

[Asar 2015, Joint Models](Asar-2015-joint.pdf)


I've attached two review papers on methods for modelling exposures measured dynamically over time and their relation to a time-to-event outcome. We've examined the Cox model with time-varying covariates and flexible models for dose, but when and how should the alternatives be used? 

The first paper, by Asar et al., reviews the methods for joint modelling of longitudinal and time-to-event data. The authors claim that joint models should be preferred over Cox models when the longitudinal data are measured infrequently or with error. The second paper, by Andersen et al., introduces the concept of multi-state models. This is a powerful approach for modelling complex event history data such as competing risks or recurrent events. 

I will present a brief overview including some examples and lead the discussion. For future topics, please let me know if you are interested in taking the lead. The planned topics for the next few months are below.

October: Sensitivity Analysis
November: Qualitative Interactions
December: Causal Inference in Observational Studies

