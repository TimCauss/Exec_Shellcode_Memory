# Execution de Shellcode

### Premier exercice d'apprentissage de création de Malware.

Dans cet exercice nous avons vu comment faire une allocation mémoire de la taille du shellcode que nous avons prédéfinis.
Nous ecrivons ensuite le shellcode dans cette mémoire allouée, et finalement nous executons le shellcode dans un nouveau thread.

Ce code est purement à des fins éducation et doit être utilisé avec prudence.

## Fonctionnalités 
 - Allocation de méoire avec les droits d'exécution.
 - Copie du shellcode dans la mémoire allouée.
 - Exécution du shellcode dans un nouveau thread.
 - Libération de la mémoire allouée après l'exécution.

## Prérequis 
Pour compiler et exécuter ce programme, vous aurez besoin de :

- Un système d'exploitation Windows.
- Un compilateur C compatible avec Windows.

## Avertissement
Ce programme exécute un shellcode arbitraire en mémoire. Le shellcode inclus dans cet exemple est destiné à des fins de démonstration et ne devrait pas causer de dommages. 
Néanmois, l'exécution de shellcode arbitraire peut être dangereuse. Utilisez ce code à vos propres risques.

