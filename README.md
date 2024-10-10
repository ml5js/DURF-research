# ml5.js DURF Projects

> “The [Deans' Undergraduate Research Fund (DURF)](https://shanghai.nyu.edu/academics/undergraduate-research) awards funding to undergraduates at NYU Shanghai for summer research in any field of study. The DURF broadly defines research as scholarly or artistic activities that lead to the production of new knowledge; to increased problem solving capabilities, including design and analysis; to original, critical or historical theory and interpretation; or to the production of art or artistic performance.”

## Summer 2023

| Project                                                                    | Student(s)                                                                                    | Advisor                            | Status                                                                                                                         |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | -----------------------------------| ------------------------------------------------------------------------------------------------------------------------------ |
| _Machine Learning for Interactive Media Artists and Education with ml5.js_ | [@ch3926](https://github.com/ch3926) [@VivianChenyc5519](https://github.com/VivianChenyc5519) | [@gohai](https://github.com/gohai) | **Incorporated** [#40](https://github.com/ml5js/ml5-next-gen/pull/40) [#43](https://github.com/ml5js/ml5-next-gen/pull/43) |
| _Implementing ml5.js library - updating models and functions_              | [@B2xx](https://github.com/B2xx) [@UpKindLikeWater](https://github.com/UpKindLikeWater)       | [@gohai](https://github.com/gohai) | **Incorporated** [#42](https://github.com/ml5js/ml5-next-gen/pull/42)                                                      |

#### Summary

Summer of 2023 had us busy starting to re-build ml5.js, based on an up-to-date version of tensorflow.js and more modern models (such as BlazePose): **Connie** and **Vivian** greatly contributed to this effort by re-implementing BodyPix based on the latest BodySegmentation API. Connie also addressed some issues with ml5's Sentiment Analysis functionality. **Zhuolin** and **Zhou** meanwhile re-implemented FaceMesh using the simpler API of ml5.js v1.

## Summer 2024

| Project                                                                                                              | Student(s)                                                                                                                                     | Advisor                            | Status                                                                                                                                     |
| -------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| _Enabling Sequential Data Modeling in ml5.js for Educational and Artistic Applications_                              | [@mop9047](https://github.com/mop9047)                                                                                                         | [@gohai](https://github.com/gohai) | **PR available** [#192](https://github.com/ml5js/ml5-next-gen/pull/192)                                     |
| _Re-Implementing the ml5.objectDetection() in ml5.js function through custom class support and improved performance_ | [@douaaz](https://github.com/douaaz) [@SherabCodes](https://github.com/SherabCodes)                                                            | [@MOQN](https://github.com/MOQN)   | **PR available** [#195](https://github.com/ml5js/ml5-next-gen/pull/195)                                     |
| _Implementing image segmentation in ml5.js_                                                                          | [@chanel1130](https://github.com/chanel1130) [@Lisa-HuangZijin](https://github.com/Lisa-HuangZijin) [@Ricci-Liu](https://github.com/Ricci-Liu) | [@gohai](https://github.com/gohai) | **Prototype completed** [ml5-extra-imagesegmentation](https://github.com/ml5js/ml5-extra-imagesegmentation) |

#### Summary

**Mathew** explored ways ml5’s NeuralNetwork can be extended to cover time series data, by using LSTM-type networks. Possible applications include different forms of gesture recognition, or predicting numeric values from sensors (e.g. concerning the weather). **Douaa** and **Sherab** worked on reimplementing Object Detection, which was one of the few remaining functionalities that we wanted to bring over from the “old” to the “new” ml5. **Chanel**, **Ruiqi** and **Zijin** (**Lisa**) explored the feasibility of real-time image segmentation in the browser using transformers.js. The project resulted in an experimental prototype that added an ImageSegmentation class to ml5 (using the detr-resnet-50-panoptic model and transformers.js) - as well as a series of creative explorations of how this functionality could be used in a creative coding context.


### Acknowledgements

Many thanks to the entire ml5.js community for providing mentorship, support and encouragement to all projects ❤️
