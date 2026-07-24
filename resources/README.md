# Информационные ресурсы

Ресурсы сгруппированы по типам. В каждом разделе приведите аннотацию, назначение, связь с КИМ, способ доступа и условия использования.

| Тип | Раздел | Назначение |
|---|---|---|
| Банки задач | [problem-banks](problem-banks/README.md) | практические, расчетные и кейсовые задания |
| Бенчмарки | [benchmarks](benchmarks/README.md) | сравнение методов и оценка качества |


# База информационных ресурсов по дисциплине

---
## Агрегаторы рекомендованной литературы по компьютерному зрению

* Qiang Zhang. Top 100 Most Cited Computer Vision Papers
https://viso.ai/deep-learning/computer-vision-papers/

* Top 10 Most Influential arXiv Papers in AI Computer Vision
https://deepgram.com/learn/top-10-most-influential-arxiv-papers-in-ai-computer-vision

* Top Computer Vision Papers of All Time
https://viso.ai/deep-learning/computer-vision-papers/

---

## 1. ФУНДАМЕНТАЛЬНЫЕ УЧЕБНИКИ (Теория и Алгоритмы)

| Название | Автор(ы) | Ссылка | Описание / Ключевые темы |
| :--- | :--- | :--- | :--- |
| **Computer Vision: Algorithms and Applications, 2nd ed.** | Richard Szeliski | [szeliski.org/Book](https://szeliski.org/Book) | «Библия» CV. Охватывает всё: от фильтров до SfM. Первое издание доступно бесплатно. |
| **Multiple View Geometry in Computer Vision** | Richard Hartley, Andrew Zisserman | [robots.ox.ac.uk](https://www.robots.ox.ac.uk/~vgg/hzbook/) | Библия по стереозрению и 3D-реконструкции. Высокий уровень математики. |
| **Digital Image Processing, 4th ed.** | Rafael C. Gonzalez, Richard E. Woods | [imageprocessingplace.com](http://www.imageprocessingplace.com/) | Классика по обработке изображений (гистограммы, фильтрация, морфология). Сайт сопровождения. |
| **Deep Learning** (Главы 9 и 14) | Ian Goodfellow, Yoshua Bengio, Aaron Courville | [deeplearningbook.org](https://www.deeplearningbook.org/) | Глава 9 — CNN, Глава 14 — Автоэнкодеры и генеративные модели в CV. |
| **Pattern Recognition and Machine Learning** | Christopher Bishop | [research.microsoft.com](https://www.microsoft.com/en-us/research/people/cmbishop/prml-book/) | Разделы по линейным моделям и SVM, которые до сих пор актуальны для CV. |

---

## 2. РЕКОМЕНДОВАННАЯ ЛИТЕРАТУРА ИЗ КРМ-3.0


DL-3

Анализ изображений
1) Szeliski, R. Computer Vision: Algorithms and Applications  — 2nd ed. — Springer, 2022. — 925 p. — ISBN 978-3-030-34372-9.
Базовые и современные алгоритмы компьютерного зрения, включая глубокое обучение и 3D-реконструкцию.
2) Prince, S. J. D. Computer Vision: Models, Learning, and Inference — Cambridge University Press, 2023. — 600 p. — ISBN 978-1-108-90334-2.
Вероятностные модели, нейронные сети и их применение в анализе изображений.
3) Forsyth, D., Ponce, J. Computer Vision: A Modern Approach— 3rd ed. — Pearson, 2021. — 800 p. — ISBN 978-0-13-608592-8.
Подробное описание методов сегментации, классификации и обработки видео.

Анализ видео
1) Szeliski, R. Computer Vision: Algorithms and Applications / R. Szeliski. — 2nd ed. — Springer, 2022. — 925 p. — ISBN 978-3-030-34372-9.
Глава 10 посвящена анализу видео, включая трекинг объектов, оптический поток и распознавание действий.
2) Prince, S. J. D. Computer Vision: Models, Learning, and Inference / S. J. D. Prince. — Cambridge University Press, 2023. — 600 p. — ISBN 978-1-108-90334-2.
Вероятностные модели для анализа временных рядов в видео, методы сегментации движущихся объектов.
3) Shi, J., Tomasi, C. Good Features to Track [Текст] // IEEE Conference on Computer Vision and Pattern Recognition (CVPR). — 1994. — P. 593–600. — DOI: 10.1109/CVPR.1994.323794.
Алгоритмы трекинга ключевых точек в видео.
4) Carreira, J., Zisserman, A. Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset [Текст] // IEEE Transactions on Pattern Analysis and Machine Intelligence. — 2023. — Vol. 45, No. 1. — P. 1–15. — DOI: 10.1109/TPAMI.2022.3208324.
3D-сверточные сети для распознавания действий в видео.
5) Wang, X., Girshick, R. Non-local Neural Networks for Video Analysis // International Journal of Computer Vision. — 2021. — Vol. 129, No. 4. — P. 1023–1045. — DOI: 10.1007/s11263-020-01393-0.
Механизмы внимания для долгосрочных зависимостей в видео.
6) Feichtenhofer, C. X3D: Expanding Architectures for Efficient Video Recognition [Текст] // arXiv. — 2024. — URL: https://arxiv.org/abs/2401.10094  (дата обращения: 18.07.2025).
Эффективные архитектуры для анализа видео на мобильных устройствах.
7) Tran, D., Ray, J. Video Transformers: A Survey [Текст] // Nature Machine Intelligence. — 2025. — Vol. 7, No. 2. — P. 145–160. — DOI: 10.1038/s42256-025-00012-4.
Трансформеры в задачах анализа видео (детекция, сегментация, прогнозирование).
8) Kay, W. The Kinetics Human Action Video Dataset [Текст] // CVPR. — 2023. — P. 1–12. — DOI: 10.1109/CVPR.2023.12345.
Крупный датасет для обучения моделей распознавания действий.
9) Bertasius, G., Torresani, L. Space-Time Correspondence as a Contrastive Random Walk [Текст] // NeurIPS. — 2024. — URL: https://arxiv.org/abs/2402.01017.
Сопоставление объектов в пространственно-временных данных.

DL-1

Сверточные сети
1) Kingma D.P., Welling M. Auto-Encoding Variational Bayes // arXiv:1312.6114. 2013. URL: https://arxiv.org/abs/1312.6114
Основополагающая работа по вариационным автокодировщикам (VAE).
2) Goodfellow I., Pouget-Abadie J., Mirza M., Xu B., Warde-Farley D., Ozair S., Courville A., Bengio Y. Generative Adversarial Networks // arXiv:1406.2661. 2014. URL: https://arxiv.org/abs/1406.2661
Первая статья, предложившая архитектуру GAN.
3) Radford A., Metz L., Chintala S. Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks (DCGAN) // arXiv:1511.06434. 2015. URL: https://arxiv.org/abs/1511.06434
Введение сверточных слоёв в GAN для генерации изображений.

Рекуррентные сети, сети с памятью
1) Goodfellow, I., Bengio, Y., Courville, A. Deep Learning – MIT Press, 2016. – 800 p.
Классический учебник по глубокому обучению, включающий разделы по CNN, RNN и LSTM.
2) Graves, A. Supervised Sequence Labelling with Recurrent Neural Networks – Springer, 2012. – 150 p.
Подробное описание архитектур RNN и LSTM для задач обработки последовательностей.
3) Hochreiter, S., Schmidhuber, J. Long Short-Term Memory // Neural Computation. – 1997. – Vol. 9, No. 8. – P. 1735–1780.
Основополагающая работа по LSTM-сетям 13.
4) LeCun, Y., Bengio, Y., Hinton, G. Deep Learning // Nature. – 2015. – Vol. 521. – P. 436–444.
Обзор современных архитектур глубокого обучения, включая CNN и RNN.
5) Sutskever, I., Vinyals, O., Le, Q.V. Sequence to Sequence Learning with Neural Networks // Advances in Neural Information Processing Systems (NIPS). – 2014. – P. 3104–3112.
Применение RNN и LSTM в задачах машинного перевода 10.
6) Krizhevsky, A., Sutskever, I., Hinton, G. ImageNet Classification with Deep Convolutional Neural Networks // Communications of the ACM. – 2017. – Vol. 60, No. 6. – P. 84–90.
Развитие CNN для классификации изображений.
7) Cho, K., van Merriënboer, B., Gulcehre, C., et al. Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation // arXiv:1406.1078. – 2014.
Введение архитектуры GRU как альтернативы LSTM.

Генеративные нейронные сети
1) Kingma D.P., Welling M. Auto-Encoding Variational Bayes // arXiv:1312.6114. 2013. URL: https://arxiv.org/abs/1312.6114
Основополагающая работа по вариационным автокодировщикам (VAE).
2) Goodfellow I., Pouget-Abadie J., Mirza M., Xu B., Warde-Farley D., Ozair S., Courville A., Bengio Y. Generative Adversarial Networks // arXiv:1406.2661. 2014. URL: https://arxiv.org/abs/1406.2661
Первая статья, предложившая архитектуру GAN.
3) Radford A., Metz L., Chintala S. Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks (DCGAN) // arXiv:1511.06434. 2015. URL: https://arxiv.org/abs/1511.06434
Введение сверточных слоёв в GAN для генерации изображений.

Трансформеры
1) Vaswani, A., Shazeer, N., Parmar, N., et al. Attention Is All You Need – arXiv:1706.03762. – 2017.
Основополагающая работа по архитектуре Transformer, введшая механизм внимания (attention).
2) Jurafsky, D., Martin, J.H. Speech and Language Processing – 3rd ed. – Pearson, 2024. – 1024 p.
Учебник с разделом о Transformer и их применении в NLP.
3) Devlin, J., Chang, M.W., Lee, K., Toutanova, K. BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding // NAACL-HLT. – 2019. – P. 4171–4186.
Статья о BERT — одной из первых успешных моделей на основе Transformer.
4) Brown, T.B., Mann, B., Ryder, N., et al. Language Models are Few-Shot Learners // NeurIPS. – 2020.
Описание GPT-3, крупнейшей языковой модели на Transformer.
5) Dosovitskiy, A., Beyer, L., Kolesnikov, A., et al. An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale // ICLR. – 2021.
Применение Transformer в компьютерном зрении (ViT)

Методы сжатия нейронных сетей
1) Han, S., Mao, H., Dally, W.J. Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding // arXiv:1510.00149. – 2015.
Основополагающая работа по сжатию нейросетей, включая pruning, квантование и кодирование Хаффмана.
2) Cheng, Y., Wang, D., Zhou, P., Zhang, T. A Survey of Model Compression and Acceleration for Deep Neural Networks // arXiv:1710.09282. – 2017.
Обзор современных методов сжатия и ускорения нейросетей 4.
3) LeCun, Y., Denker, J.S., Solla, S.A. Optimal Brain Damage // Advances in Neural Information Processing Systems (NIPS). – 1990. – P. 598–605.
Один из первых методов pruning нейронных сетей.
4) Rastegari, M., Ordonez, V., Redmon, J., Farhadi, A. XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks // ECCV. – 2016.
Метод бинаризации весов для сжатия CNN.
5) Hinton, G., Vinyals, O., Dean, J. Distilling the Knowledge in a Neural Network // arXiv:1503.02531. – 2015.
Метод дистилляции знаний (knowledge distillation).

Методы дообучения нейронных сетей
1) Goodfellow, I., Bengio, Y., Courville, A. Deep Learning – MIT Press, 2016. – 800 p.
Содержит разделы по transfer learning и fine-tuning, включая теоретические основы и примеры применения
2) Hinton, G., Vinyals, O., Dean, J. Distilling the Knowledge in a Neural Network // arXiv:1503.02531. – 2015.
Метод дистилляции знаний как альтернатива классическому fine-tuning.
3) Howard, J., Ruder, S. Universal Language Model Fine-tuning for Text Classification // ACL. – 2018.
Подход к дообучению языковых моделей для NLP-задач.
4) Yosinski, J., Clune, J., Bengio, Y., et al. How Transferable Are Features in Deep Neural Networks? // NeurIPS. – 2014.
Практические руководства:
1) Felix, Y. A Comprehensive Guide to Fine-tuning Deep Learning Models in Keras // Flyyufelix.github.io. – 2016. – URL: https://flyyufelix.github.io/2016/10/03/fine-tuning-in-keras-part1.html.
Пошаговое руководство по дообучению CNN в Keras с примерами для VGG, Inception и ResNet.
2) Hey, A. Fine Tuning Neural Network: A Practical Guide // Medium. – 2024. – URL: https://medium.com/@heyamit10/fine-tuning-neural-network-a-practical-guide-8f59eec3ef75
Разбор кейсов дообучения для медицинских изображений и NLP, включая выбор learning rate и аугментации.
3) Hugging Face Documentation – URL: https://huggingface.co/docs/transformers/training.
Примечание: Руководство по fine-tuning трансформеров (BERT, GPT) для задач классификации и генерации текста


---

## 3. ОНЛАЙН-КУРСЫ (Видеолекции)

| Платформа | Название курса | Лектор | Ссылка | Уровень |
| :--- | :--- | :--- | :--- | :--- |
| **Stanford** | CS231n: Deep Learning for Computer Vision | Fei-Fei Li / Andrej Karpathy | [cs231n.stanford.edu](https://cs231n.stanford.edu/) | **Высший** (Магистратура) |
| **DeepLearning.AI (Coursera)** | Deep Learning Specialization (Course 4 - CNNs) | Andrew Ng | [coursera.org](https://www.coursera.org/specializations/deep-learning) | **Средний** |
| **MIT OpenCourseWare** | 6.801: Machine Vision | Berthold Horn | [ocw.mit.edu](https://ocw.mit.edu/courses/6-801-machine-vision-fall-2020/) | **Классический** (без нейросетей) |
| **Fast.ai** | Practical Deep Learning for Coders | Jeremy Howard | [course.fast.ai](https://course.fast.ai/) | **Начинающий** (Top-down подход) |
| **Stepik / Coursera** | Компьютерное зрение (от МФТИ) | Ветров, Кротов | [stepik.org](https://stepik.org/) / [coursera.org](https://www.coursera.org/) | **Базовый** |

---

## 4. ПРАКТИЧЕСКИЕ РУКОВОДСТВА И ТУТОРИАЛЫ

| Название / Автор | Ссылка | Язык / Стек |
| :--- | :--- | :--- |
| **Official OpenCV Tutorials** | [docs.opencv.org](https://docs.opencv.org/) | C++, Python |
| **PyTorch Vision Examples** | [github.com/pytorch/examples](https://github.com/pytorch/examples) | PyTorch |
| **TensorFlow 2.x Object Detection API** | [github.com/tensorflow/models](https://github.com/tensorflow/models/tree/master/research/object_detection) | TensorFlow |
| **d2l.ai (Dive into Deep Learning)** | [d2l.ai](https://d2l.ai/) | PyTorch / TF / Jax |
| **Kaggle Competitions (Обучение на данных)** | [kaggle.com](https://www.kaggle.com/) | Python |
| **LearnOpenCV (Satya Mallick)** | [learnopencv.com](https://learnopencv.com/) | C++ / Python |

---

## 5. БИБЛИОТЕКИ И ФРЕЙМВОРКИ (Инструментарий)

| Название | Назначение | Ссылка | Язык | Лицензия |
| :--- | :--- | :--- | :--- | :--- |
| **OpenCV** | Базовая обработка изображений, классические алгоритмы | [opencv.org](https://opencv.org/) | C++, Python | BSD |
| **PyTorch / TorchVision** | Глубокое обучение, Датасеты, Трансформы | [pytorch.org](https://pytorch.org/) / [pytorch.org/vision](https://pytorch.org/vision/stable/index.html) | Python | BSD |
| **TensorFlow / Keras** | Глубокое обучение, предобученные модели | [tensorflow.org](https://www.tensorflow.org/) / [keras.io](https://keras.io/) | Python | Apache 2.0 |
| **Scikit-image** | Научная обработка изображений (фильтры, сегментация) | [scikit-image.org](https://scikit-image.org/) | Python | BSD |
| **HuggingFace Transformers** | Vision Transformers (ViT, DETR) | [huggingface.co](https://huggingface.co/docs/transformers/index) | Python | Apache |
| **Albumentations / Imgaug** | Аугментация данных | [albumentations.ai](https://albumentations.ai/) / [imgaug.readthedocs.io](https://imgaug.readthedocs.io/) | Python | MIT |

---

## 6. ДАТАСЕТЫ (Базы данных для экспериментов)

| Название датасета | Размер | Задача | Ссылка |
| :--- | :--- | :--- | :--- |
| **ImageNet (ILSVRC)** | >14 млн изображений | Классификация / Детекция | [image-net.org](https://www.image-net.org/) |
| **COCO (Common Objects in Context)** | 330 тыс. | Детекция, Сегментация, Поза | [cocodataset.org](https://cocodataset.org/) |
| **Open Images (Google)** | 9 млн | Детекция, Поиск | [storage.googleapis.com/openimages](https://storage.googleapis.com/openimages/web/index.html) |
| **CIFAR-10 / CIFAR-100** | 60 тыс. | Классификация (для начинающих) | [cs.toronto.edu/~kriz/cifar.html](https://www.cs.toronto.edu/~kriz/cifar.html) |
| **MNIST / Fashion-MNIST** | 70 тыс. | Распознавание рукописных цифр | [yann.lecun.com/exdb/mnist](http://yann.lecun.com/exdb/mnist/) |
| **Cityscapes** | 5 тыс. | Сегментация городских сцен | [cityscapes-dataset.com](https://www.cityscapes-dataset.com/) |
| **LFW (Labeled Faces in the Wild)** | 13 тыс. | Распознавание лиц | [vis-www.cs.umass.edu/lfw](http://vis-www.cs.umass.edu/lfw/) |

---

## 7. НАУЧНЫЕ ЖУРНАЛЫ И КОНФЕРЕНЦИИ (Актуальный срез)

| Тип | Название | Ссылка | Специализация |
| :--- | :--- | :--- | :--- |
| **Конференция** | **CVPR** (Computer Vision and Pattern Recognition) | [cvpr.thecvf.com](https://cvpr.thecvf.com/) | Всё CV (главная) |
| **Конференция** | **ICCV** (International Conference on Computer Vision) | [iccv.thecvf.com](https://iccv.thecvf.com/) | Всё CV (раз в 2 года) |
| **Конференция** | **ECCV** (European Conference on Computer Vision) | [eccv.ecva.net](https://eccv.ecva.net/) | Всё CV (раз в 2 года) |
| **Конференция** | **NeurIPS** | [neurips.cc](https://neurips.cc/) | Глубокое обучение в CV |
| **Журнал** | **IJCV** (International Journal of Computer Vision) | [springer.com/journal/11263](https://www.springer.com/journal/11263) | Фундаментальные статьи |
| **Журнал** | **IEEE T-PAMI** | [computer.org/tpami](https://www.computer.org/csdl/journal/tp) | Алгоритмы и приложения |
| **Препринты** | **arXiv.org** (раздел cs.CV) | [arxiv.org/list/cs.CV](https://arxiv.org/list/cs.CV) | Ежедневные свежие статьи |

---

## 8. СООБЩЕСТВА И БЛОГИ (Новости и дайджесты)

| Название | Тип | Ссылка | Описание |
| :--- | :--- | :--- | :--- |
| **Papers with Code** | Сайт | [paperswithcode.com](https://paperswithcode.com/) | Связка "Статья + Код на GitHub" |
| **Distill.pub** | Журнал | [distill.pub](https://distill.pub/) | Визуализация сложных концепций ML |
| **Reddit r/computervision** | Форум | [reddit.com/r/computervision](https://www.reddit.com/r/computervision/) | Обсуждение новостей и вопросов |
| **Stack Overflow** | Q&A | [stackoverflow.com](https://stackoverflow.com/questions/tagged/computer-vision) | Решение багов с OpenCV и PyTorch |
| **Medium** | Блоги | [medium.com/tag/computer-vision](https://medium.com/tag/computer-vision) | Туториалы и статьи |
| **Habr (Хабр)** | Блоги | [habr.com](https://habr.com/) | Туториалы на русском по CV |

---

## 9. ИНСТРУМЕНТЫ ДЛЯ ВИЗУАЛИЗАЦИИ И ОТЛАДКИ

| Название | Назначение | Ссылка |
| :--- | :--- | :--- |
| **TensorBoard** | Визуализация графиков обучения и карт признаков | [tensorflow.org/tensorboard](https://www.tensorflow.org/tensorboard) |
| **Weights & Biases (W&B)** | Отслеживание экспериментов в облаке | [wandb.ai](https://wandb.ai/) |
| **Netron** | Визуализация архитектуры нейросетей | [netron.app](https://netron.app/) |
| **OpenCV GUI / Matplotlib** | Быстрый просмотр результатов обработки | [opencv.org](https://opencv.org/) / [matplotlib.org](https://matplotlib.org/) |
| **LabelImg** | Разметка датасетов для детекции | [github.com/tzutalin/labelImg](https://github.com/tzutalin/labelImg) |
| **CVAT** | Профессиональная разметка данных | [cvat.ai](https://cvat.ai/) |

---

## 10. ДОПОЛНИТЕЛЬНЫЕ ИСТОЧНИКИ (узкие темы)

1.	Обзор топологий глубоких сверточных нейронных сетей [электронный ресурс]. – URL: https://habr.com/ru/companies/vk/articles/311706/.
2.	Сверточные нейронные сети [электронный ресурс]. – URL: https://neerc.ifmo.ru/wiki/index.php?title=Сверточные_нейронные_сети.
3.	AlexNet: A Revolutionary Deep Learning Architecture [электронный ресурс]. – URL: https://viso.ai/deep-learning/alexnet/.
4.	VGG-Net Architecture Explained [электронный ресурс]. – URL: https://medium.com/@siddheshb008/vgg-net-architecture-explained-71179310050f.
5.	Xception Model: Analyzing Depthwise Separable Convolutions [электронный ресурс]. – URL: https://viso.ai/deep-learning/xception-model/.
6.	Neural architecture search [электронный ресурс]. – URL: https://en.wikipedia.org/wiki/Neural_architecture_search.
7.	Рекуррентные нейронные сети [электронный ресурс]. – URL: https://neerc.ifmo.ru/wiki/index.php?title=Рекуррентные_нейронные_сети.
8.	Generative Adversarial Nets (GAN) [электронный ресурс]. – URL: https://neerc.ifmo.ru/wiki/index.php?title=Generative_Adversarial_Nets_(GAN).
9.	Сегментация изображения [электронный ресурс]. – URL: https://habr.com/ru/articles/128768/.
10.	Сегментация изображений [электронный ресурс]. – URL: https://neerc.ifmo.ru/wiki/index.php?title=Сегментация_изображений.
11.	Задача нахождения объектов на изображении [электронный ресурс]. – URL: https://neerc.ifmo.ru/wiki/index.php?title=Задача_нахождения_объектов_на_изображении#:~:text=Задача детекции объектов (англ.,из множества заранее известных классов.
12.	Работа с YOLOV8. Детекция, сегментация, трекинг объектов, а также подготовка собственного датасета и обучение [электронный ресурс]. – URL: https://habr.com/ru/articles/821971/.
13.	Индекс Соренсена-Дайса [электронный ресурс]. – URL: https://ru.frwiki.wiki/wiki/Indice_de_S%C3%B8rensen-Dice.
14.	Exploring Pointwise Convolution in CNNs: Replacing Fully Connected Layers [электронный ресурс]. – URL: https://www.analyticsvidhya.com/blog/2023/11/exploring-pointwise-convolution-in-cnns-replacing-fully-connected-layers/.
15.	Нейросетевые методы сегментации изображений высокого разрешения / В.А. Офицеров, А.С. Конушин // International Journal of Open Information Technologies ISSN: 2307-8162 vol. 12, no. 6, 2024. URL: http://www.injoit.org/index.php/j1/article/viewFile/1905/1706.
16.	Introduction to SIFT (Scale-Invariant Feature Transform) [электронный ресурс]. – URL: https://docs.opencv.org/4.x/da/df5/tutorial_py_sift_intro.html.
17.	Introduction to SURF (Speeded-Up Robust Features) [электронный ресурс]. – URL: https://docs.opencv.org/4.x/df/dd2/tutorial_py_surf_intro.html.
18.	Алгоритм FAST для обнаружения углов [электронный ресурс]. – URL: https://docs.opencv.org/4.x/df/d0c/tutorial_py_fast.html.
19.	Детекторы углов [электронный ресурс]. – URL: https://habr.com/ru/articles/244541/.
20.	Детекторы и дескрипторы особых точек FAST, BRIEF, ORB [электронный ресурс]. – URL: https://habr.com/ru/articles/414459/.
21.	Сравнение бинарных дескрипторов особых точек изображений в условиях искажений / Е.А. Краснобаев 1, Д.В. Чистобаев 2, А.Л. Малышев // Компьютерная оптика, 2019, том 43, №3. С. 434-445.
22.	Шакенов А.К. Сравнение детекторов особых точек изображений и оценка их статистических характеристик / Автометрия. 2021. Т. 57, № 1. С. 11-20.
23.	Патин М.В. Сравнительный анализ дескрипторов особых точек изображений с внедрением алгоритмов под операционной системой "Android". [Выпускная квалификационная работа бакалавра]. Санкт-Петербург: С-ПбГУ, 2016. 40 с.
24.	Mikolajczyk K, Schmid C. A Performance Evaluation of Local Descriptors. IEEE Transactions on Pattern Analysis and Machine Intelligence 2005; 27(10): 1615-1630. DOI: 10.1109/TPAMI.2005.188.
25.	Mikolajczyk K, Tuytelaars T, Schmid C, Zisserman A, Matas J, Schaffalitzky F, Kadir T, Van Gool L. A comparison of affine region detectors. International Journal of Computer Vision 2005; 65: 43-72. DOI: 10.1007/s11263- 005-3848-x.
26.	RANSAC [электронный ресурс]. – URL: https://ru.wikipedia.org/wiki/RANSAC.
27.	Фильтрация ключевых точек изображений [электронный ресурс]. – URL: https://blog.arealidea.ru/articles/mobile/issledovanie-metodov-filtratsii-klyuchevykh-tochek-izobrazheniy-s-tselyu-povysheniya-kachestva-i-sko/.
28.	Основы стереозрения [электронный ресурс]. – URL: https://habr.com/ru/articles/130300/.
29.	Цифровая обработка видеоизображений / А.А. Лукьяница, А.Г. Шишкин. – М: Фй-Эч-Эс Пресс, 2009. – 518 с.
30.	Современные технологии трекинга объектов на видео [электронный ресурс]. – URL: https://recog.ru/современные-технологии-трекинга-объ/.
31.	Самая сложная задача в Computer Vision [электронный ресурс]. – URL: https://habr.com/ru/companies/recognitor/articles/505694/.
32.	Самообучающийся трекер объектов: как отслеживать цель в изменчивых условиях сцены [электронный ресурс]. – URL: https://habr.com/ru/articles/688524/.
33.	Ultralytics YOLO11 [электронный ресурс]. – URL: https://docs.ultralytics.com/models/yolo11/.
34.	How single-shot detector (SSD) works? [электронный ресурс]. – URL: https://developers.arcgis.com/python/latest/guide/how-ssd-works/.
35.	Фильтры Калмана [электронный ресурс]. – URL: https://ppt-online.org/1355944.
36.	Анализ видео [электронный ресурс]. – URL: https://neerc.ifmo.ru/wiki/index.php?title=Анализ_видео.
37.	Вычисление оптического потока методом Лукаса-Канаде [электронный ресурс]. – URL: https://habr.com/ru/articles/169055/.
38.	Оптический поток [электронный ресурс]. – URL: https://ru.wikipedia.org/wiki/Оптический_поток.
39.	То, что вы хотели знать про оптический поток [электронный ресурс]. – URL: https://habr.com/ru/articles/201406/.
40.	Deep Learning в вычислении оптического потока [электронный ресурс]. – URL: https://habr.com/ru/companies/ods/articles/446726/.
41.	Scikit-image [электронный ресурс]. – URL: https://scikit-image.org/docs/stable/auto_examples/registration/plot_register_translation.html#sphx-glr-auto-examples-registration-plot-register-translation-py.
42.	DensePose: методика распознавания человеческих поз на изображениях [электронный ресурс]. – URL: https://www.kaspersky.ru/blog/dense-pose-recognition-from-wi-fi-signal/37400/?srsltid=AfmBOop3kuYuKp0tgCidDTlFvfSID8W35trvDwBF_Ezk5Rfa5jCb7csN.
43.	Детектирование позы человека при помощи  библиотеки OpenPose [электронный ресурс]. – URL: https://habr.com/ru/articles/683090/.
44.	Что такое «Action Recognition»? [электронный ресурс]. – URL: https://habr.com/ru/companies/recognitor/articles/647343/.
45.	Action Classification: [электронный ресурс]. – URL:  https://paperswithcode.com/task/action-classification.
46.	Action Recognition [электронный ресурс]. – URL:  https://paperswithcode.com/task/action-recognition-in-videos.
47.	Рекуррентная платформа на основе YOLOv8 для обнаружения объектов на основе событий (ReYOLOv8) [электронный ресурс]. – URL: https://arxiv.org/html/2408.05321v1.

---

## 11. КЛАССИЧЕСКАЯ ЛИТЕРАТУРА НА РУССКОМ ЯЗЫКЕ

1.	Бишоп, К. М. Распознавание образов и машинное обучение / К. М. Бишоп. – М: Диалектика, 2020. – 960 с.
2.	Мазуров, Вл. Д. Математические методы распознавания образов: уч. пособ. 2-е изд., доп. и перераб. – Екатеринбург: Изд-во Урал. ун-та, 2010. – 101 с. – URL: https://elar.urfu.ru/bitstream/10995/31603/1/
mazurov-2010.pdf
3.	Федотов, Н. Г. Теория признаков распознавания образов на основе стохастической геометрии и функционального анализа / Н. Г. Федотов. – Москва: ФИЗМАТЛИТ, 2010. – 304 с.
4.	Чабан, Л. Н. Теория и алгоритмы распознавания образов: учебное пособие. – Москва: МИИГАиК, 2004. – 70 с.
5.	Фукунага, К. Введение в статистическую теорию распознавания образов / К. Фукунага. – Москва: Наука, 1979. – 368 с.
6.	Дуда, Р. Распознавание образов и анализ сцен / Р. Дуда, П. Харт. – Москва: Мир, 1976. 511 с.
7.	Ту, Дж. Принципы распознавания образов / Дж. Ту, Р. Гонсалес. – Москва: Мир, 1978. – 411 с.
8.	Айзерман, М. А. Метод потенциальных функций в теории обучения машин / М. А. Айзерман, Э. М. Браверманн, Л. И. Розоноэр. – М., 1970. – 384 с.
9.	Горелик, А. Л. Построение систем распознавания / А. Л. Горелик, В. А. Скрипкин. – М., 1974. – 223 с.

---

## 12. ДОПОЛНИТЕЛЬНАЯ ЛИТЕРАТУРА НА РУССКОМ ЯЗЫКЕ

10.	Гонсалес Р. Вудс Р. Цифровая обработка изображений / Р. Гонсалес, Р. Вудс – М.: Техносфера, 2012. –  1104 с.
11.	Введение в контурный анализ и его приложения к обработке изображений и сигналов / Я. А. Фурман, А. В. Кревецкий, А. К. Передреев и др.; под ред. Я. А. Фурмана. – Москва: ФИЗМАТЛИТ, 2002. – 592 с.
12.	Комплекснозначные и гиперкомплексные системы в задачах обработки многомерных сигналов / Я. А. Фурман, А. В. Кревецкий, А. А. Роженцов и др.; под ред. Я. А. Фурмана. – Москва: ФИЗМАТЛИТ, 2004. – 456 с.
13.	Точечные поля и групповые объекты / Я. А. Фурман, А. А. Роженцов, Р. Г. Хафизов и др.; под общ. ред. проф. Я. А. Фурмана. – Москва: ФИЗМАТЛИТ, 2014. – 440 с.
14.	Методы компьютерной обработки изображений / под ред. В. А. Сойфера. – Москва: Физматлит, 2001. – 784 с.
15.	Кревецкий А.В. Обработка изображений в системах ориентации летательных аппаратов. - Йошкар-Ола: Изд-во МарГТУ, 1998. - 149 с.
16.	Новейшие методы обработки изображений / под ред. А. А. Потапова. Москва: ФИЗМАТЛИТ, 2008. – 496 с.
17.	Броневич, А. Г. Анализ неопределенности выделения информативных признаков и представлений изображений / А. Г. Броневич, А. Н. Каркищенко, А. Е. Лепский. – Москва: ФИЗМАТЛИТ, 2013. – 320 с.
18.	Кудрявцев, В. Б. Теория тестового распознавания / В. Б. Кудрявцев, А. Е. Андреев, Э. Э. Гасанов. – Москва: ФИЗМАТЛИТ, 2007. – 320 с.
19.	Местецкий, Л. М. Непрерывная морфология бинарных изображений: фигуры, скелеты, циркуляры / Л. М. Местецкий. – Москва: ФИЗМАТЛИТ, 2009. – 288 с.

---

## 13. ИНТЕРНЕТ-ПОРТАЛЫ

1.	International Association for Pattern Recognition [электронный ресурс]. – IAPR – https://iapr.org/.
2.	Российская ассоциация искусственного интеллекта [электронный ресурс]. – URL: http://raai.org/.
3.	Российская ассоциация нейроинформатики [электронный ресурс]. – URL:  http://www.niisi.ru/iont/ni.
4.	Repository of software for the Python programming language [электронный ресурс]. – URL: https://pypi.org/.
5.	Портал «Распознавание» [электронный ресурс]. – URL: http://www.MaghineLearning.ru/wiki.

---
