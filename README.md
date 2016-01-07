# Self-Disclosure Items Dataset

Distributed together with: Anonymity, Intimacy and Self-Disclosure in Social Media (full citation below).

## Description:

This dataset contains self-disclosure items with various levels of intimacy and valence. The items can be used to study self disclosure under various settings. We also include below the source data from an experiment that used these items to study the effect of anonymity and audience on comfort level of self-disclosure. 

### Self-discolsure Items

The details of the item development are provided in the paper. We developed 36 items (18 positive, 18 negative) that cover six topical categories:

(1) Tastes and Interests;

(2) Attitudes and Opinions;

(3) Work or Studies;

(4) Economic and Social Status;

(5) Interpersonal Relations and Self-Concept;

(6) Physical Appearance and Sex;

* The items are available in ``self-disclosure-items.csv`` file that contains:
	- id
	- text
	- category
	- valence
	- intimacy mean and standard deviation (N = 269) as detailed in the paper

### Source Data from Anonymity and Self-disclosure Experiment

We used the self-disclosure items to run a Mechanical Turk experiment to investigate how the identification and audience features of the social media platform design moderate the relationship between content intimacy and willingness to self-disclose. details of the experiment and participant recruiting are provided in the paper. 

* The ``experiment-data.csv`` contains participant responses used in the analysis (N = 269) after the filtering process detailed in the paper. The file contains multiple rows, each including:
	- participant id
	- condition assigned
	- intimacy rating given by the participant
	- willingness to self-disclose
	- age
	- gender
	- area of residence (Urban/Suburban/Rural)
	- social media use (general, Facebook, Twitter, Instagram, Snapchat, Secret, Yik Yak, Whisper)

* The ``experiment-raw.csv`` contains all participant responses (N = 307) including ones filtered as possible spam. The file contains the same columns as above.


## BibTeX Entry:

@inproceedings{ma2016,
  author={Ma,Xiao and Hancock, Jeff and Naaman, Mor},
  title={Anonymity, Intimacy and Self-Disclosure in Social Media},
  booktitle={Proceedings of the 2016 CHI Conference on Human Factors in Computing Systems},
  series={CHI '16},
  year={2016}
}
