# Is It Possible to Attack a T2I Model With Only Punctuation?

## Abstract

Text-to-Image (T2I) models have become immensely popular due to their ability to generate high quality images from natural language prompts, but their safety and robustness in real-world applications remains a critical concern to date. In this work, we explore the use of punctuations as an attack vector on black-box T2I models. We show that it is easy to fool and mislead the victim model by simply injecting a few punctuations into the clean prompt, despite punctuations having virtually no semantic meaning. These punctuations injected could be attributed to human typographical errors, making the adversarial attack imperceptible and suitable as a real-world attack. We also propose the Punctuation Injection Permutator (PIP) pipeline which can craft the adversarial prompt automatically using an optimizer and a vision-language model (VLM) evaluator in both untargeted and targeted attack settings.

## How to Use

Use the Jupyter notebooks (.ipynb) with the prefix `[PIPELINE]` in the main directory. You can then modify the file according to your needs.

Our evaluation results can be found in the `eval` directory.

## Report and Citations

Technical details of the project are described in `Is It Possible to Attack a T2I Model With Only Punctuation.pdf` in the main directory.
