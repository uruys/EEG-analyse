# EEG-analyse

J'ai réalisé ce projet afin de mieux comprendre comment les signaux EEG peuvent être utilisés pour analyser l'activité cérébrale et détecter des anomalies comme les crises épileptiques.

L'objectif de ce projet est de distinguer des signaux EEG correspondant à une activité cérébrale normale de ceux associés à une crise épileptique. L'EEG permet d'enregistrer l'activité électrique du cerveau et est souvent utilisé pour étudier certaines pathologies neurologiques.

J'ai commencé par charger les données EEG et observer leur structure. Chaque ligne correspond à un signal EEG et contient des mesures de l'activité électrique au cours du temps. J'ai ensuite séparé les données en deux groupes : les signaux normaux et les signaux associés aux crises épileptiques.

J'ai visualisé les signaux EEG afin d'observer directement les différences d'activité cérébrale entre les deux groupes. J'ai ensuite appliqué la transformée de Fourier pour analyser le contenu fréquentiel des signaux, puis un filtre passe-bande pour éliminer les fréquences parasites qui ne correspondent pas à une activité cérébrale. Enfin, j'ai calculé la puissance des signaux afin de mesurer l'intensité de cette activité électrique.

On peut en déduire que les signaux EEG contiennent des caractéristiques qui permettent de distinguer différents états de l'activité cérébrale. Pendant une crise épileptique, les neurones présentent une activité anormale et plus synchronisée, ce qui modifie le signal EEG. Ces différences peuvent être détectées grâce à l'analyse des données.

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- Jupyter Notebook
