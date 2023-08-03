# The 1st Scientific Figure Captioning (SciCap) Challenge

Welcome to the 1st Scientific Figure Captioning (SciCap) Challenge! This challenge brings fun and innovation to the world of research, AI, NLP, and CV by combining these fields to create computational models for generating useful text for visuals. Hosted in the 5th Workshop on Closing the Loop Between Vision and Language at ICCV 2023 (Paris, France), the SciCap Challenge features *cash prizes* for the best-performing models!

You'll have access to an astounding 400,000 scientific figure images from various arXiv papers, along with their respective captions and relevant paragraphs. Your mission is to leverage this data to build models capable of generating accurate and informative captions for these images.

## Challenge Structure 🚀

The challenge follows a two-phase structure: the **Test Phase** and the **Challenge Phase**.

- **Test Phase**: Lasts approx. 2.5 months, where you build and test models using the provided training set, validation set, and **public test set**.
- **Challenge Phase**: Takes place over the final 2 weeks before the submission deadline. A **hidden test set** is released, and you'll submit your results for this set.

Winning teams will be determined based on their best results for the hidden test set.


## Baseline Code

Please follow the instructions on [SciCap.AI](http://scicap.ai/) to download the dataset. 
Put all the json files under `scicap-data/` folder.

Install the required package. 
`pip install -r requirements.txt`

Note: Python version >=3.6, <= 3.9

Run the baseline code:
`bash train.sh`

Note: Our baseline code is based on [huggingface summarization](https://github.com/huggingface/transformers/tree/main/examples/pytorch/summarization). We only use text for fine-tuning. You can adapt this script on your own need.

## Evaluation Code

[Scicap_evaluation.ipynb](Scicap_evaluation.ipynb)


## Important Dates 🗓️

- SciCap Challenge launches: May 29, 2023
- Test Phase begins: May 29, 2023, 12:00 AM (CST)
- Challenge Phase begins (hidden test set released): August 15, 2023, 12:00 AM (CST)
- Challenge Phase ends: August 31, 2023, 23:59 PM (CST)
- Technical report submission deadline: September 4, 2023
- Challenge result notification: September 6, 2023
- Workshop date: TBA

## Prizes and Recognition 🏆

There will be two cash prize winners:

1. **Leaderboard Winner ($300 USD)** - The team with the highest automatic evaluation score across the entire hidden test set.
2. **Quality Winner ($300 USD)** - The team with the best automatic evaluation score from a human-curated subset of the hidden test set containing higher-quality captions.

Are you excited to join the 1st SciCap Challenge? Then head over to the [challenge page](https://github.com/Crowd-AI-Lab/figure-captioning-challenge) to find all the information you need to participate, including data, code, baselines, evaluation criteria, and important dates. Don't forget to submit your results to [Eval.AI](https://eval.ai/web/challenges/challenge-page/2012/overview) before the deadline and provide a report (2-4 pages) detailing your system using the ICCV 2023 paper template.

For any questions about the challenge, feel free to email the organizers at [**scicap-challenge@googlegroups.com**](mailto:scicap-challenge%40googlegroups.com).

Best of luck! We can't wait to see your innovative and groundbreaking captioning models! 🌟
