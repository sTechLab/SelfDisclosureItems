# Self-Disclosure Items Dataset

Distributed together with: Anonymity, Intimacy and Self-Disclosure in Social Media

## Description:

This dataset contains 36 evaluated self-disclosure items (18 positive, 18 negative) that cover six topical categories:

(1) Tastes and Interests;

(2) Attitudes and Opinions;

(3) Work or Studies;

(4) Economic and Social Status;

(5) Interpersonal Relations and Self-Concept;

(6) Physical Appearance and Sex;

* The ``self-disclosure-items.csv`` file contains:
	- id
	- text
	- category
	- valence
	- intimacy mean and standard deviation (N = 269) as detailed in the paper


* The ``experiment-data.csv`` contains participant responses used in the analysis (N = 269) after the filtering process detailed in the paper:
	- participant id
	- condition assigned
	- intimacy rating given by the participant
	- willingness to self-disclose
	- age
	- gender
	- area of residence (Urban/Suburban/Rural)
	- social media use (general, Facebook, Twitter, Instagram, Snapchat, Secret, Yik Yak, Whisper)

* The ``experiment-raw.csv`` contains all participant responses (N = 307).


## BibTeX Entry:

@inproceedings{ma2016,
  author={Ma,Xiao and Hancock, Jeff and Naaman, Mor},
  title={Anonymity, Intimacy and Self-Disclosure in Social Media},
  booktitle={Proceedings of the 2016 CHI Conference on Human Factors in Computing Systems},
  series={CHI '16},
  year={2016}
}