---

date: 2026-09-16T13:48

tags: []

up: 

---
# Pseudocode de la suite de Wallis

## Premier niveau

1. message à l'utilisateur
2. saisie du terme de Wallis
3. si le terme saisi est correct
	1. calculer l'approximation de Wallis
	2. afficher le résultat
4. sinon
	1. afficher un message d'erreur
5. afficher un message de fin

## Deuxième niveau

1. message de bienvenue
2. saisie du termes de Wallis
	1. saisie du numérateur
		1. invitation à le saisir
		2. saisie de l'utilisateur
	2. saisie du dénominateur
		1. invitation à le saisir
		2. saisie de l'utilisateur
3. vérification des termes saisies
	1. le numérateur est pair et positif
	2. le dénominateur est impair et positif
	3. dénominateur - numérateur = |1|
4. si le terme saisi est incorrect
	1. afficher un message d'erreur
	2. terminer le programme
5. si le terme saisi en incorrect
	1. afficher un message d'erreur
	2. terminer le programme
6. si la combinaison du dénominateur/numérateur est correct
	1. calculer l'approximation de la suite de Wallis
		1. premier terme = 2 / 1
		2. numérateur > dénominateur
			1. augmenter de 2 le dénominateur pour le prochain terme
		3. dénominateur > numérateur 
			1. augmenter de 2 le numérateur pour le prochain terme
		4. multiplier result par le prochain terme
		5. si newTerm != saisie de l'utilisateur
			1. recommencer depuis le 6.2
		6. si newTerm = saisie de l'utilisateur
			1. arrêter la boucle
	2. afficher le résultat
7. sinon
	1. afficher un message d'erreur
8. afficher un message de fin