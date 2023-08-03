# Masterthesis "Einsatz von Transfer Learning bei der Verarbeitung multispektraler Fernerkundungsdaten mit Deep Learning"

Dieses Repository ergänzt die Masterthesis mit o.g. Titel.
Neben dem Programmcode im Ordner "code" sind ebenfalls YAML-Files vorhanden um die verwendeten Environments zu replizieren und eine Übersicht des verwendeten U-Net.

Der Programmcode gliedert sich in:
- model_config_files:\
  Die JSON-Dateien, mit Hilfe derer die Modelle geladen werden.
- create_UNet.ipynb\
  Das Notebook, welches verwendet wurde um das verwendete U-Net zu erstellen, die Config-JSON zu exportieren und die vortrainierten Gewichte zu extrahieren.
- preprocess_data.ipynb:\
  Das Notebook, welches verwendet wurde um die Daten vorzubereiten.
- run_tensorflow.ipynb:\
  Das Notebook, mit dem die Versuche durchgeführt wurden.

Alle notwendigen Dateien finden sich ebenfalls unter: LINK ZU ABGABE CLOUD
Hier stehen neben der Arbeit selbst auch die verwendeten Gewichte und der Datensatz zur Verfügung.
