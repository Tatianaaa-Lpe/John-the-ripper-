Présentation du projet

Le projet présenté a pour but d'utiliser le logiciel John-the-ripper afin de tester la robustesse de mot de passe sur un poste client. 
Ces tests sont exécutés via des VM, une machine serveur et une machine client.

Introduction:

John-the-ripper c'est quoi?

John-the-ripper est un logiciel de cassage de mot de passe utilisé, par exemple, pour tester la robustesse de mot de passe. Il a d'abord été développer pour tourner sous des systèmes dérivés d'UNIX mais le programme fonctionne aujourd'hui sous d'autres plateformes.
Il est l'un des logiciels les plus populaires car il inclut une autodétection des fonctions de hachage utilisée pour stocker les mots de passe. (Fonction de hachage: une fonction mathématique qui brouille les données pour les rendre illisibles).

Source Wikipédia.
 
Les actions qu'il peut faire:

John-the-ripper à plusieurs modes d'action. Les plus fréquentes sont les méthodes:
  
> simple (utilisation du nom utilisateur pour casser les mots de passe les plus simples)
> Par dictionnaire (utilise une liste de mots en utilisant aussi le nom utilisateur)
> Incrémental il essayera toutes les combinaisons possibles

Bien évidemment, plus un mot de passe est compliqué, plus sa recherche sera longue.

John-the-ripper peut casser des mots de passe avec différentes fonctions de hachage avec des algorithmes comme MD5, blowfish, Kerberos, AFS, et les LM hashes de Windows NT/2000/XP/2003. 
On peut le complèter avec des modules additionnels pour qu'il puisse casser des mots de passe basés sur les hash MD4 ainsi que MySQL, LDAP, NTLM.






