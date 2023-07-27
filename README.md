# GAL - Generate, Attribute, Localize

This repo accompanies the post on the GAL approach from [Back to Building](https://crosley.substack.com/) on creating fine-grained explanations for LLM outputs.

See the notebooks here:
* [Traditional QA Notebook](/traditional_qa/traditional_qa.ipynb)
* [Audio GAL Notebook](/audio_gal/audio_with_gal.ipynb)
* [PDF GAL Notebook](/pdf_gal/pdf_with_gal.ipynb)

Install the necessary dependencies by running:
```
python3.11 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Set up your environment variables with the following command (and add your API keys)
```
cp .env.example .env.local
```