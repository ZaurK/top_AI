
### Ключевые бенчмарки компьютерного зрения

#### Классификация изображений
| Название | Описание | Ссылка |
| :--- | :--- | :--- |
| **ImageNet (ILSVRC)** | Фундаментальный бенчмарк, который drove early deep learning progress. Соревнования на этом датасете, такие как ILSVRC, стали стандартом для сравнения моделей классификации. Состоит из более чем 14 миллионов изображений. | [image-net.org](https://www.image-net.org/) |
| **CIFAR-10 / CIFAR-100** | Меньшие и более простые датасеты, идеально подходящие для быстрого прототипирования и проверки идей ("sanity checks"). | [cs.toronto.edu](https://www.cs.toronto.edu/~kriz/cifar.html) |

#### Обнаружение объектов (Object Detection)
| Название | Описание | Ссылка |
| :--- | :--- | :--- |
| **COCO (Common Objects in Context)** | "Go-to" бенчмарк для обнаружения объектов, сегментации и описания изображений. Использует метрику mean Average Precision (mAP) и охватывает широкий круг повседневных объектов. | [cocodataset.org](https://cocodataset.org/) |
| **Pascal VOC** | Более старый, но все еще полезный бенчмарк для простых задач детекции и исторических сравнений. | - |

#### Сегментация (Segmentation)
| Название | Описание | Ссылка |
| :--- | :--- | :--- |
| **Cityscapes** | Основной бенчмарк для сегментации городских сцен (например, для задач беспилотных автомобилей). | [cityscapes-dataset.com](https://www.cityscapes-dataset.com/) |
| **ADE20K** | Часто используется для более широкого понимания сцены и семантической сегментации. | [groups.csail.mit.edu](https://groups.csail.mit.edu/vision/datasets/ADE20K/) |
| **COCO** | Также широко используется для сравнения в задачах сегментации экземпляров (instance segmentation). | [cocodataset.org](https://cocodataset.org/) |

#### 3D Восприятие и Автономные системы
| Название | Описание | Ссылка |
| :--- | :--- | :--- |
| **KITTI** | Один из первых и самых известных бенчмарков для задач восприятия в условиях вождения. | [cvlibs.net](https://www.cvlibs.net/datasets/kitti/) |
| **nuScenes** | Более современный мультисенсорный датасет для оценки детекции, трекинга и понимания сцены. | [nuscenes.org](https://www.nuscenes.org/) |
| **Waymo Open Dataset** | Крупный датасет от Waymo для тех же задач, что и nuScenes. | [waymo.com/open](https://waymo.com/open/) |

#### Понимание видео (Video Understanding)
| Название | Описание | Ссылка |
| :--- | :--- | :--- |
| **Kinetics** | Стандартный бенчмарк для распознавания действий в видео. | - |
| **Something-Something** | Бенчмарк, проверяющий способность модели рассуждать о тонких действиях и их контексте. | - |

#### Мультимодальные модели и агенты
| Название | Описание | Ссылка |
| :--- | :--- | :--- |
| **ImageNet-D** | Оценивает робастность классификаторов к искажениям, используя синтетические изображения от диффузионных моделей. | [GitHub](https://github.com/chenshuang-zhang/imagenet_d) |
| **Polaris** | Оценивает способность Vision-Language моделей следовать инструкциям в интерактивной среде. | - |
| **VBench** | Комплексный бенчмарк для генеративных видеомоделей. | - |
| **GRAB** | Сложный бенчмарк для оценки больших мультимодальных моделей (LMMs). | [GitHub](https://github.com/jonathan-roberts1/GRAB) |
| **Titan CV Benchmark** | Бенчмарк для оценки производительности **агентов** (agent) в области компьютерного зрения. | [Hugging Face](https://huggingface.co/DataCanvasAILab/Titan-CV-Agent-Benchmark) |
| **UI-Vision** | Бенчмарк для автономных агентов, работающих с графическими интерфейсами в реальных приложениях. | [GitHub](https://github.com/uivision/UI-Vision) |

#### Системные и аппаратные бенчмарки
| Название | Описание | Ссылка |
| :--- | :--- | :--- |
| **MLPerf** | Отраслевой стандарт для измерения скорости обучения и инференса на различных аппаратных стеках. | [mlcommons.org](https://mlcommons.org/) |
| **UL Procyon AI Computer Vision Benchmark** | Измеряет производительность инференса для задач CV на Windows-устройствах. | [benchmarks.ul.com](https://benchmarks.ul.com/) |
| **AI Benchmark** | Приложение для оценки AI-производительности мобильных устройств, включая задачи CV. | [AI-Benchmark.com](http://ai-benchmark.com) |
| **Ultralytics Benchmarks** | Сравнение производительности моделей YOLO на различных NVIDIA GPU. | [ultralytics.com](https://www.ultralytics.com/ru/benchmarks) |
