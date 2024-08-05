# Direct Preference Optimization for LLM Fine-tuning

## Overview
This study applies the technique presented in the "Direct Preference Optimization" paper to fine-tune large language models (LLMs) so that they better understand and align with human preferences. The goal is to improve the LLM's ability to produce results that are both accurate and consistent with human values and preferences.

## Objective
The primary goal of this study is to use direct preference optimization approaches to better the alignment of LLM results to human evaluation norms. This involves training models on a dataset annotated with human preferences, allowing the models to generate more user-friendly material.

## How It Works - **Data Collection**: Gathering data samples to reflect diverse human preferences.
- Annotating these samples with preferences using a manner matched with the one suggested in in the paper.
- Fine-tuning a pre-trained LLM with the annotated dataset, focusing on optimizing for these preferences.
- Measuring the performance of the fine-tuned model with both automated measures and human evaluations to ensure alignment with human preferences.


## Next Steps:
- Figure out how to evaluate model performance [Reference Article](https://ritikjain51.medium.com/llms-fine-tuning-and-evaluation-f019515b1c67)
- Iteratively following the above process for 3 iterations and evaluate model performance

## Generated preference dataset
https://huggingface.co/datasets/AmarNagargoje/preferred_dataset2

## License
This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE.md) file for details.

## Acknowledgements
- Inspired by the techniques proposed in the "Direct Preference Optimization" paper.

## Contact
For any queries or discussions regarding the project, please open an issue in the GitHub repository, reach out to me via [LinkedIn](https://www.linkedin.com/in/amarcs/)  or contact me directly at nagargoje.a@northeastern.edu.

## Citation
```
@inproceedings{
    rafailov2023direct,
    title={Direct Preference Optimization: Your Language Model is Secretly a Reward Model},
    author={Rafael Rafailov and Archit Sharma and Eric Mitchell and Christopher D Manning and Stefano Ermon and Chelsea Finn},
    booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
    year={2023},
    url={https://arxiv.org/abs/2305.18290}
}
```

## References used
- [Fine Tuned Model: snorkelai/Snorkel-Mistral-PairRM-DPO](https://huggingface.co/snorkelai/Snorkel-Mistral-PairRM-DPO)
- [Dataset: snorkelai/Snorkel-Mistral-PairRM-DPO-Dataset](https://huggingface.co/datasets/snorkelai/Snorkel-Mistral-PairRM-DPO-Dataset)
- [Fine-tune Llama 2 with DPO: HuggingFace Blog](https://huggingface.co/blog/dpo-trl)
- [Article: DPO-Fine-Tuning for Enhanced Language Model Performance](https://medium.com/@mauryaanoop3/dpo-fine-tuning-for-enhanced-language-model-performance-466fec349a5e)
- [PairRM Model](https://huggingface.co/llm-blender/PairRM)
- [GitHub DPO Implementation](https://github.com/eric-mitchell/direct-preference-optimization)
- [YouTube Video - Mistra-7B Inference](https://www.youtube.com/watch?v=eovBbABk3hw&ab_channel=Rohan-Paul-AI)
- [Inferencing Mistral-7B](https://github.com/rohan-paul/LLM-FineTuning-Large-Language-Models/blob/main/Mistral-7B-Inferencing.ipynb)