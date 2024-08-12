# Detection and Mitigation of Multimodal Adversarial Attacks

This repository contains the research materials, code, and results for our study on detecting and mitigating multimodal adversarial attacks on Large Language Models (LLMs).

## Abstract

In the rapidly evolving field of AI, ensuring the robustness of Large Language Models (LLMs) against adversarial attacks is mandatory. This study investigates the impact of combining adversarial images with regular images on targeted LLM's outputs and proposes strategies to combat these vulnerabilities. Utilizing techniques such as FGSM and PGD, we generated adversarial images and assessed their effects on models like ChatGPT and DALL-E. Our findings reveal significant vulnerabilities, highlighting the need for robust defense mechanisms. We propose adversarial training, defensive distillation, input preprocessing, ensemble methods, and regularization as mitigation strategies.

## Repository Structure (**WIP**)

- `poster/`: Contains the research poster presented at GMIS.
- `code/`: Includes all the Python scripts used for data collection, adversarial image generation, detection techniques, and mitigation strategies.
- `data/`: Stores the datasets used in the study (CIFAR-10, ImageNet, and custom Fisheye Dataset).
- `results/`: Contains the figures and other output from our experiments.
- `references/`: Includes a bibliography of references used in this research.

## Key Findings

- Adversarial attacks can significantly affect the performance of AI models, leading to incorrect or harmful outputs.
- The effectiveness of adversarial attacks increases with the magnitude of perturbation (epsilon value).
- Detection techniques such as Feature Squeezing, Local Intrinsic Dimensionality (LID), and Neural Network Ensembles show promise in identifying adversarial examples.

## Future Work

Future research should explore additional detection methods, refine reversion techniques, and test on a broader range of models and datasets.

## Acknowledgments

This material is based upon work supported by the National Science Foundation under Grants numbers CNS-2137791, and HRD-1834620. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the authors and do not necessarily reflect the views of the National Science Foundation.

## Contact

For more information, please contact Dejaun Gayle at dejaun.scholar@gmail.com.
