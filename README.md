## ViSAGe: A Global-Scale Analysis of Visual Stereotypes in Text-to-Image Generation

This repository contains data resources for the paper "[ViSAGe: A Global-Scale Analysis of Visual Stereotypes in Text-to-Image Generation](https://arxiv.org/abs/2401.06310)."


### Overview

Recent studies have shown that Text-to-Image (T2I) model generations can reflect social stereotypes present in the real world. However, existing approaches for evaluating stereotypes have a noticeable lack of coverage of global identity groups and their associated stereotypes. To address this gap, we introduce the ViSAGe (Visual Stereotypes Around the Globe) dataset to enable the evaluation of known nationality-based stereotypes in T2I models, across 135 nationalities. We enrich an existing textual stereotype resource by distinguishing between stereotypical associations that are more likely to have visual depictions, such as `sombrero', from those that are less visually concrete, such as 'attractive'. We demonstrate ViSAGe's utility through a multi-faceted evaluation of T2I generations. First, we show that stereotypical attributes in ViSAGe are thrice as likely to be present in generated images of corresponding identities as compared to other attributes and that the offensiveness of these depictions is especially higher for identities from Africa, South America, and Southeast Asia. Second, we assess the stereotypical pull of visual depictions of identity groups, which reveals how the 'default' representations of all identity groups in ViSAGe have a pull towards stereotypical depictions, and that this pull is even more prominent for identity groups from the Global South. 


## Dataset Description

The repo contains the data cards for the ViSAGe dataset, following the format proposed by [Pushkarna et al.](https://arxiv.org/abs/2204.01075). The data card includes details of the dataset such as intended usage, field names and meanings, annotator recruitment, and payments. The file `visual_attributes` contains the annotations for the visual nature of attributes as denoted on a Likert Scale ranging from "Strongly Agree" to "Strongly Disagree". The file `Image_Annotations` contains annotations for the presence or absence of attributes in the images along with their co-ordinates.


## Citation

```
@inproceedings{jha-2024-beyond,
  title={ViSAGe: A Global-Scale Analysis of Visual Stereotypes in Text-to-Image Generation},
  author={Jha, Akshita and Prabhakaran, Vinodkumar and Denton, Remi and Laszlo, Sarah and Dave, Shachi and Qadri, Rida and Reddy, Chandan K and Dev, Sunipa},
  journal={arXiv preprint arXiv:2401.06310},
  year={2024}
}
```

