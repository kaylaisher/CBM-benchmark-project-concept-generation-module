# Concept Bottleneck Models benchmark project : unify concept generation module

## features

 - Support openai style api key, urls
 - Support local host llm
 - Async query
 - ready-to-used concepts to train VLG-CBM, LF-CBM, LaBo, LM4CV, and CB-LLM
 - interactive user entrance to choose models and datasets

# installation

```bash
# Clone the repo
git clone https://github.com/kaylaisher/CBM-benchmark-project-concept-generation-module.git
cd CBM-benchmark-project-concept-generation-module
```

# run the code

```bash
python run.py
```


## Sources

#### If you use this library, please also cite the foundational works:

#### T. Oikarinen, S. Das, L. Nguyen and T.-W. Weng, Label-free Concept Bottleneck Models, ICLR 2023.
```
@inproceedings{oikarinen2023labelfree,
  title     = {Label-free Concept Bottleneck Models},
  author    = {Oikarinen, Tuomas and Das, Subhro and Nguyen, Lam M and Weng, Tsui-Wei},
  booktitle = {International Conference on Learning Representations},
  year      = {2023}
}
```

#### Srivastava, Divyansh and Yan, Ge and Weng, Tsui-Wei, VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance, NeurIPS 2024.
```
@inproceedings{srivastava2024vlg,
  title   = {VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance},
  author  = {Srivastava, Divyansh and Yan, Ge and Weng, Tsui-Wei},
  booktitle = {NeurIPS},
  year    = {2024}
}
```

#### Yang, Yue and Panagopoulou, Artemis and Zhou, Shenghao and Jin, Daniel and Callison-Burch, Chris and Yatskar, Mark, Language in a Bottle: Language Model Guided Concept Bottlenecks for Interpretable Image Classification
```
@inproceedings{yang2023language,
  title={Language in a bottle: Language model guided concept bottlenecks for interpretable image classification},
  author={Yang, Yue and Panagopoulou, Artemis and Zhou, Shenghao and Jin, Daniel and Callison-Burch, Chris and Yatskar, Mark},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={19187--19197},
  year={2023}
}
```

#### An Yan, Yu Wang, Yiwu Zhong, Chengyu Dong, Zexue He, Yujie Lu, William Wang,  Jingbo Shang, Julian J. McAuley, Learning Concise and Descriptive Attributes for Visual Recognition
```
@article{DBLP:journals/corr/abs-2308-03685,
  author       = {An Yan and
                  Yu Wang and
                  Yiwu Zhong and
                  Chengyu Dong and
                  Zexue He and
                  Yujie Lu and
                  William Wang and
                  Jingbo Shang and
                  Julian J. McAuley},
  title        = {Learning Concise and Descriptive Attributes for Visual Recognition},
  journal      = {CoRR},
  volume       = {abs/2308.03685},
  year         = {2023}
}
```
