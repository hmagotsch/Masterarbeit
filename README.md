Das vorliegende GitHub-Repository enthält mit zwei .h5- und acht Python-Dateien den gesamten Quellcode, um die Ergebnisse der Forschungsarbeit reproduzieren zu können. Die .h5 Dateien sind die trainierten CNNs und in den Python-Dateien werden die XAI-Techniken auf die CNNs angewandt. Der Quellcode der einzelnen Python-Dateien wurde mit Hilfe von Chat-GPT überarbeitet (Strukturierung und Fehlerbehebung). Die genaue Funktion der einzelnen Dateien wird im Folgenden kurz erläutert.

cifar10_model01.h5: Das trainierte einfache CNN, welches auf den CIFAR-10-Datensatz trainiert wurde.

cifar10_resnet34.h5: Das bereits vortrainierte ResNet34.

CNN_allgemein: Das einfache CNN wird auf den CIFAR-10-Datensatz angewandt. Dabei wird die Genauigkeit des Netzes insgesamt, aber auch für jede Klasse bestimmt. Außerdem wird für jede Klasse der Index der richtig und falsch klassifizierten Bilder ausgegeben.

CNN_LIME: Auf das einfache CNN wird LIME angewandt. Es können dabei unterschiedliche Konfigurationen vorgenommen werden.

CNN_SHAP: Auf das einfache CNN wird SHAP angewandt. Es können dabei unterschiedliche Konfigurationen vorgenommen werden.

CNN_Grad-CAM: Auf das einfache CNN wird Grad-CAM angewandt. Es können dabei unterschiedliche Convolutional-Layer ausgewählt werden.

ResNet34_allgemein: Das ResNet34 wird auf den CIFAR-10-Datensatz angewandt. Dabei wird die Genauigkeit des Netzes insgesamt, aber auch für jede Klasse bestimmt. Außerdem wird für jede Klasse der Index der richtig und falsch klassifizierten Bilder ausgegeben.

ResNet34_LIME: Auf das ResNet34 wird LIME angewandt. Es können dabei unterschiedliche Konfigurationen vorgenommen werden.

ResNet34_SHAP: Auf das ResNet34 wird SHAP angewandt. Es können dabei unterschiedliche Konfigurationen vorgenommen werden.

ResNet34_Grad-CAM: Auf das ResNet34 wird Grad-CAM angewandt. Es können dabei unterschiedliche Convolutional-Layer ausgewählt werden.
