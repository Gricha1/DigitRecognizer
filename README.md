# DigitRecognizer
Здесь представлен код для соревнования  https://www.kaggle.com/c/digit-recognizer/code?competitionId=3004   по распознаванию рукописных цифр.
Классификатор выдает качество (Accuracy) = 0.98353, написано при помощи PyTorch.

# ГиперПараметры
На данный момент помогло выбить такой скор: 
модель - ResNet101 с заморозкой первых 5-ти слоев(grad_required), optimizator = Adamax, LossFunc = CrossEntropyLoss.


