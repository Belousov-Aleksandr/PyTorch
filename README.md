Данный репозиторий содержит работы по годичному курсу Deep Learning School МФТИ (https://www.dlschool.org).
DLS – учебная организация на базе Физтех-школы прикладной математики и информатики Московского физико-технического института.
Основной фреймворк - PyTorch
* CNN with Simpsons. Соревнование на Kaggle.
Classification Simpsons-persons (Bart, Gomer, Lisa.....42 classes) on Kaggle. Public Score 0.99681. Models - EfficientNet - 0, 1, 2, 3, 4. Augmentation, over-sampling, etc.
* Autoencoders (AE, VariationalAE, ConditionalVAE)
Представлены 3 модели класса Автоэнкодеров (VanillaAE, VariationalAE, ConditionalVAE). Пайплайн содержит разделы: загрузка данных, архитектура модели, обучение с визуализацией, семплирование и два бонусных раздела: Denoising (удаление шума с изображения), поиск двойников (схожих лиц) по фотофрейму. Размер латентного пространства для обработки фотографий равен 512, исходный shape изображения (128,128,3). Сжатие 96 раз. Лосс 0.000777. Для обработки MNIST latent_dim = 4.
* GAN (convolution). Face peoples.
Генератор лиц людей на базе сверточных GAN-сетей (LabelSmoothing, TTUR, augmentation, TSNE-преобразование, LeaveOneOut)
* Сегментация объектов
SegNet, UNet, Unet2 vs BCE, Dice, Focal, Lovasz and awesome inference :-) All loss function made as custom implementation.
* sklearn, CatBoost, XGBoost, imblearn, Kaggle
Предсказание оттока пользователей. Соревнование на Kaggle.
* NLP
Базовый уровень NLP (токенизация, лемматизация, ранжирование, эмбединги, классификация на RNN (LSTM), CNN).
Средний уровень NLP (скрытые цепи Маркова, алгоритм Виттерби, Part-Of-Speech Tagger, LstmTagger, NLTK, Rnnmorph,
Mashine_Translatation (bidirectional Seq2Seq with concat_Attention))
Продвинутый уровень NLP (GPT2 (Sequence Classification on Twitter Dataset, BERT (Sentence Sentiment Classification),Summarization)
