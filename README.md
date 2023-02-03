# Wiki GPT

Code to generate [GPT-wiki-intro dataset](https://huggingface.co/datasets/aadityaubhat/GPT-wiki-intro#overview).
This dataset can be used to train and evaluate mdoels to classify text as human written or GPT generated.

To run the code
    1. Install requirements from requirements.txt
    2. Create config.py and add your `OPENAI_API_KEY`
    3. Create a `data` folder
    4. Run `process_wiki_data.ipynb`
    5. Run `download_openai.ipynb`
    6. Run `process_results.ipynb`

## Citation

Please cite as following

```
@misc {aaditya_bhat_2023,
    author       = { {Aaditya Bhat} },
    title        = { GPT-wiki-intro (Revision 0e458f5) },
    year         = 2023,
    url          = { https://huggingface.co/datasets/aadityaubhat/GPT-wiki-intro },
    doi          = { 10.57967/hf/0326 },
    publisher    = { Hugging Face }
}
```
