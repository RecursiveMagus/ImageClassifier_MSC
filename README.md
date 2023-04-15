# Projecte final de classificació d'Imatges amb Pytorch+fastai
Repositori per la pràctica final de classificació d'imatges de l'assignatura de Adv. Machine Learning del MCD de la UdG, implementada per:

- Isaac de Palau (u??????)
- Joan Saló (u1953621)


Tot seguit s'especifiquen els apartats que apareixen en aquest repositori, juntament amb alguns detalls adicionals:

### 1. Baseline

Proves elementals. Fer les proves sense transformacions a les imatges, "tal qual" venen al dataset. Provar amb resnets 18->152, donat que són les xarxes de transfer learning més modernes.

### 2. Aplicar transformacions

Exactament el mateix que l'apartat anterior, però aplicant transformacions sobre les imatges.

### 3. LR manual

Fer servir la funció ``fit_one_cycle``, explicar-la i comentar els resultats.

### 4. Ajust d'hiperparàmetres amb GridSearchCV

Utilitzar Grid Search per ajustar al màxim els hiperparàmetres, i comentar com van variant els resultats. Com a mínim, s'hauria de provar:

  * loss_function
  * optimizer
  * learning rate
  
El millor model resnet que s'aconsegueixi en aquest apartat s'haurà de guardar.  
  
### 5. Altres arquitectures

Provar altres arquitectures estranyes i/o antigues com ara una densenet o una alexnet.

### 6. Prediccins sobre el conjunt de test

Amb la millor xarxa obtinguda, classificar les imatges del conjunt de test i guardar .CSV

### Extra 1. Entrenar "a pelo"
Crear la NN des de zero i entrenar-la. Comparar els resultats amb les xarxes preentrenades que hem estat fent servir.

### Extra 2. Explicabilitat
Experimentar amb CAM i GradCAM.

### Extra 3. Style transfer
Provar un exemple d'style transfer.
