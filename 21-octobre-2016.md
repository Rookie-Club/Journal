## Participants

- [[Hafid]]
- [[Yannick]]
- [[Simon]]


## Depuis la dernière fois

- Le wiki commence à être un vrai wiki avec des pages pour les langages, les
  outils, les personnes.
- Ce soir il y a un meetup [Programmons ensemble des objets imprimables en
  3D](https://www.meetup.com/fr-FR/Objets-3D-Programmables-app-objets/events/234970346/).
- [[Simon]] découvre que certaines évidentes pour lui ne le sont pas forcement
  pour les autres.
- [[Simon]] et [[Hafid]] ont essayé de faire une [[fourmi de langton]] en
  [[JavaScript]].
- [[Hafid]] a fait de la peinture.
- [[Hafid]] a tenté de faire pas à pas, mais il en a oublié qu'en objet il faut
  modifier un état (et donc modifier les attributs).
- L'affichage ne fonctionnait pas, par contre les tests unitaires étaient vert.
- [[Yohann]] a exploré la librairire [Numpy](http://www.numpy.org/)


## Ce matin

On regarde ce qu'[[Hafid]] à produit.

- Beaucoup de manipulation [[git]] pour replacer le code qu'Hafid a produit sur
  la mauvaise branche.
- On re-attache une branche à sa référence sur origin
- `git reset --hard HEAD^` _peut modifier le code_
- `git branch --set-upstream=origin/mabranch mabranch`
- `git branch --unset-upstream`
- `git branch -vv`
- `git cherry-pick [sha1]` à revoir. _peut modifier le code_
- `git log --decorate --graph --branches --pretty=oneline`
- `git reflog`
- `git reset --hard HEAD^` = !(`git commit -m "mon commit"`)
- `git reset --soft HEAD^` vs `git reset --hard HEAD^` ?
- Ça fait quoi le `git reset` sans le `HEAD` ? Sans le `^` ?
- `git reset --opt [cible sur laquelle on veux se repositionner]`

Ensuite, on a corrigé et fait avancer un peu le code et la fourmi

- C'est Yannick qui a beaucoup pris le clavier, du coup, on avancé
- Il est inutile de charger des fichiers dont nous n'aurons pas besoin (le
  `binding.js` dans les tests, le `spec/langton_spec.js` dans la page de
  production `index.html`).
- En cas de problème c'est une bonne idée de revenir en arrière plutôt que
  d'ajouter quelque chose.
- Impression d'avoir des doublons de fonctions entre le fichier `bindings.js`
  et `spec/langton_spec.js`.
- Cette impression est juste, mais c'est normal de tester ce que l'on cherche à
  mettre en place.

