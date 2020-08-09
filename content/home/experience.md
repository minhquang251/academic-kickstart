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
  title = "Research Assistant - VAE-Powered Vehicle Re-identification Project"
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
  title = "Research Assistant - Image-based Vehicle Re-identification Project (AI City Challenge 2020)"
  company = "TCU Department of Computer Science"
  company_url = ""
  location = Fort Worth, TX"
  date_start = "December 2019"
  date_end = "May 2020"
  description = """
  * Designed a Vehicle Re-identification pipeline to compete in 2020 AI City Challenge - CVPR 2020 workshop.
  * Adopted Detectron2 (Faster-RCNN) developed by Facebook to effectively crop image for noise reduction.
  * Proposed adaptive attention-driven model with ResNet50 backbone for Vehicle Re-identification.
  * Proposed metadata re-ranking method that takes color and type features extracted by ResNeXt101 into consideration when performing k-reciprocal re-ranking.
  * Evaluated model on CityFlow Dataset.
  """
  
 [[experience]]
  title = "Research Assistant - Beijing Housing Price Prediction Project"
  company = "TCU Department of Computer Science"
  company_url = ""
  location = "Fort Worth, TX"
  date_start = "June 2019"
  date_end = "December 2019"
  description = """
  * Researched different Machine Learning and Deep Learning methods used to forecast housing price.
  * Applied multiple techniques such as Stack Generalization or Hybrid Regression to enhance the prediction.
  * Visualized the housing price distribution of Beijing to find the correlation between price and other features.
  * Evaluated the performance of tree-based regression models on feature-rich datasets.
  * Investigated the enhancement of prediction results after combining Machine Learning and Deep Learning models.
  """
  
  [[experience]]
  title = "Research Assistant - AI-2-Go Project"
  company = "TCU Department of Computer Science"
  company_url = ""
  location = Fort Worth, TX"
  date_start = "January 2019"
  date_end = "September 2019"
  description = """
  * Re-modeled Alpha Go Zero to discover the optimal solutions for Go game.
  * Calculated the winning probability of each move using Monte Carlo Tree Search.
  * Simulated Go matches between two AIs to find the better AI version.
  * Contributed to the open source project of Alpha Go Zero, Leela Zero.
  """
  
  [[experience]]
  title = "Technical Team Member - MSU State Space Robotics Team"
  company = "MSU Department of Computer Science and Engineering"
  company_url = ""
  location = "Mississippi State, MS"
  date_start = "October 2017"
  date_end = "December 2018"
  description = """
  * Simulated environments for testing obstacle avoidance features of robots using ROS.
  * Visualized movements of multiple minibots in 2D using Python.
  * Visualized the environments in 3D using Gazebo.
  * Delivered the final robot to the yearly NASA Robotic Mining Competition.
  """

+++
