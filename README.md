# Clause Weighting and Restarts in Local Search for SAT

https://github.com/GitHubUserA0/stage_sat_m2/

The code is divided into five branches, one branch per contribution and one branch that merges them all:

* main branch: Refactored version of CCAnr

* MABs branch: Multi-Armed-Bandit version of CCAnr

* choose_cc_clauses_only branch: CCAnr CC_CLAUSES version

* Restart_keep_data branch: CCAnr weight_conservation version

* general_versions branch: CCAnr merge of all contributions

For each branch, simply download the repository. Compilation is performed using the “make” command via a makefile specific to each version (each branch contains only the appropriate makefile).

For each version, execution with default parameters is performed as follows:

{path to the executable} -inst {path to the instance}.

For more details regarding execution parameters, comprehensive and detailed documentation is available in the document located in this same repository under the name {Documentation_exhaustive.pdf}; please refer to it for further information on the execution parameters for each version of CCAnr.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Pondération de clauses et redémarrages dans la recherche locale pour SAT

https://github.com/GitHubUserA0/stage_sat_m2/

Le code est réparti en cinq branches, une branche par contribution et une branche les fusionnant toutes : 

* Branche main : CCAnr version refactorisée

* Branche MABs : CCAnr version Multi-Armed-Bandit

* Branche choose_cc_clauses_only : CCAnr version CC_CLAUSES

* Branche Restart_keep_data : CCAnr version weight_conservation

* Branche general_versions : CCAnr fusion de toutes les contributions

Pour chaque branche, il suffit de télécharger le dépot. La compilation se fait via la commande "make" grâce à un makefile spécifique à chaque version (dans chaque branche, se trouve uniquement le makefile approprié).

Pour chaque version, l'exécution avec paramètres par défaut, se fait de la manière suivante : 

{chemin vers l'exécutable} -inst {chemin vers l'instance}. 

Pour plus de détails concernant les paramètres d'exécution, une documentation exhaustive et détaillée est disponible dans le document présent dans ce même dépôt sous le nom de {Documentation_exhaustive.pdf}, veuillez vous y référer pour de plus amples informations sur les paramètres d'exécution de chaque version de CCAnr.
