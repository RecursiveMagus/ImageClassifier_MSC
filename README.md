# Projecte final de classificació d'Imatges amb Pytorch+fastai
Repositori per la pràctica final de classificació d'imatges de l'assignatura de Adv. Machine Learning del MCD de la UdG.


Tot seguit s'especifiquen els apartats que cal que apareguin al Notebook, juntament amb alguns detalls adicionals:

### 1. Baseline

Proves elementals. Fer les proves sense transformacions a les imatges, "tal qual" venen al dataset. Provar amb resnets 18->152, donat que són les xarxes de transfer learning més modernes.

### 2. Aplicar transformacions

Exactament el mateix que l'apartat anterior, però aplicant transformacions sobre les imatges.

### 3. Fit-one-cycle

Fer servir la funció ``fit_one_cycle``, explicar-la i comentar els resultats.

### 4. Ajust d'hiperparàmetres

Ajustar manualment hiperparàmetres, i comentar com van variant els resultats. Com a mínim, s'hauria de provar:

  * loss_function
  * optimizer
  * learning rate
  
El millor model resnet que s'aconsegueixi en aquest apartat s'haurà de guardar.  
  
### 5. Altres arquitectures

Provar altres arquitectures estranyes i/o antigues com ara una densenet o una alexnet.


Adicionalment, si queda prou temps, es pot afegir:

### Extra 1. GridSearchCV
Fer Grid Search CV per trobar els millors paràmeres.
### Extra 2. Entrenar "a pelo"
Crear la NN des de zero i entrenar-la. Comparar els resultats amb les xarxes preentrenades que hem estat fent servir.
### Extra 3. Transformers
Fer servir transformers com a classificadors.
### Extra 4. Style transfer
Provar un exemple d'style transfer.
### Extra 5. Reinf. Learning
Provar l'exemple clàssic del CartPole amb Convolucionals.
