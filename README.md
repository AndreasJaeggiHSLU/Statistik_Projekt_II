Statistik_Projekt_II

Projektstruktur:
Abgabe_1.0.ipynb: Das vollständige, dokumentierte Jupyter Notebook mit der statistischen Modellierung.
heart.csv: Der verwendete Datensatz (Cleveland Heart Disease Dataset).
README.md: Diese Projektbeschreibung.

---------------------------------------------------------------------------------------------------------
Liste der benötigten Python-Bibliotheken:
pandas
numpy
matplotlib
seaborn
statsmodels
jupyter

--------------------------------------------------------------------------------------------------------
Daten & Plausibilisierung
Der Datensatz stammt ursprünglich aus dem UCI Machine Learning Repository (Cleveland Datenbank).

Wichtiger Hinweis zur Datenkonsistenz:
Im Rahmen der explorativen Datenanalyse (EDA) wurde festgestellt, dass die Labels der Zielvariable (target) im vorliegenden heart.csv vertauscht waren. Entgegen der ursprünglichen UCI-Beschreibung zeigte die Validierung mittels der Variable exang (Sport-Angina), dass in diesem Datensatz gilt:

0 = Herzkrank
1 = Gesund

Dies wurde im Pre-Processing des Notebooks korrigiert und berücksichtigt.

--------------------------------------------------------------------------------------------------------



Andreas Jäggi, Januar 2026