+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 55  # Order that this section will appear.

title = "Experience"
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
  title = "Research Intern"
  company = "University of California, Berkeley"
  company_url = ""
  location = "Berkeley, USA"
  date_start = "2020-06-01"
  date_end = ""
  description = """
*Advisor* : [Dawn Song](https://people.eecs.berkeley.edu/~dawnsong/)

**Objective** : _Neural symbolic hybrids for few shot recognition_
* Using **program induction** to sample programs for **few shot image classification**. 

* Training procedure involves Supervised pre-training with **teacher-forcing** followed by reinforcement learning using [Hindsight Experience Replay](https://arxiv.org/abs/1707.01495).

* We use **memory augmented networks** with attention to allow multiple chains of execution.

**Objective** : _Meta learning in SQL query synthesis_
* Divided the [Spider](https://yale-lily.github.io/spider) dataset into 13 meta categories.

* We use **transformers** to generate embeddings for natural language question tokens.

* A **meta-training phase** for decoder to learn predicting the **structure** of SQL query

* A **domain specific training** phase for token prediction using a separate multi head attention module.
  """
[[experience]]
  title = "Visiting Research Scholar"
  company = "MPI Brain Research Institute"
  company_url = ""
  location = "Frankfurt"
  date_start = "2019-08-12"
  date_end = "2020-03-15"
  description = """
*Advisor* : [Prof. Moritz Helmstaedter](http://brain.mpg.de/research/helmstaedter-department.html)

**Objective** : _Myelin segmentation in 3D mSEM and connectomic analysis_

* We used **3D Unet** trained on **multi Scanning Electron Microscope** raw data to generate 3D segmentation masks

* Dynamically oversampling (with linearly decaying probability) myelinated voxel cubes to provide non-zero gradients countering **highly skewed data** (0.01% positively labeled voxels)

* Reached over **90% precision-recall**. Using the detection to analyze thalamocortical neurons with myelinated axons at the beginning of innervation.

  """
[[experience]]
  title = "Visiting Research Scholar"
  company = "NexT++ centre"
  company_url = ""
  location = "NUS Singapore"
  date_start = "2018-05-07"
  date_end = "2018-07-28"
  description = """
*Advisor* : [Prof. Tat Seng Chua](https://www.chuatatseng.com/)

**Objective**: _Monocular 3D object instance recognition and Pose Estimation_

* Proposed (alongside a post graduate student) a novel end-to-end architecture consisting of two modules for robust pose prediction and **3D instance recognition** via extracting **Marr’s 2.5 D sketches** from images.

* The learned embedding explicitly **disentangles** a shape vector and a pose vector,  which alleviates both pose bias for 3D shape retrieval and categorical bias for pose estimation

* One sub module learns to reconstruct 3D model, from the 2.5D sketches, in its canonical viewpoint via **multi-task learning DNNs**. Another NN sub module uses **Faster R-CNN** style anchor boxes to predict the **6 DoF** poses in continuous domain.

* The method achieves state of the art **10.3 median error** for pose estimation and **0.592 top-1-accuracy** for category agnostic 3D object retrieval on the **Pascal3D+dataset**.

"""

[[experience]]
  title = "Lead Software Developer"
  company = "New York Office"
  company_url = ""
  location = "IIT Kanpur"
  date_start = "2016-05-01"
  date_end = "2018-07-28"
  description = """
  **Objective:** _Industrial grade deployment of ML backend and android application for NYO_

* Lead a team of **16 people** at NYO.

* **ML systems:**

	*  **Collaborative Filtering** for Recommendation engine
	*  Automated response collection from handwritten characters markings on response sheets for grading
	*  NLU **chatbot** using [RASA](https://rasa.com/) pipeline with **NER, Relationship extraction** and **quantity association** for extracting required information from user.
* **Android app:**  REST APIs, SSE notifications, app-caching, Continuous integration with Jenkins, data and property binding, Reactive Java for observables



"""
+++
