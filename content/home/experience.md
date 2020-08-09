+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Research Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Undergaduate Research Assistant - VAE-Powered Vehicle Re-identification Project"
  company = "TCU Department of Computer Science"
  company_url = ""
  location = "Fort Worth, TX"
  date_start = "May 2020"
  date_end = ""
  description = """
  * Design a Vehicle Re-identification pipeline which is powered by VAE for image augmentation and filter grafting methods
for filter-level learning.
  * Design Variational Autoencoder (VAE) to reconstruct images that exclude vehicle-specific details.
  * Design convex combination function for residual images and original images to effectively enhance the salient features
before feeding images into ResNet50 backbone.
  * Evaluate the model on popular benchmarks VeRi-776 and Vehicle-1M
  """

[[experience]]
  title = "Professor"
  company = "University X"
  company_url = ""
  location = "California"
  date_start = "2016-01-01"
  date_end = "2016-12-31"
  description = """Taught electronic engineering and researched semiconductor physics."""

+++
