# The Pirate's Dice — site public

Ce qui doit etre lisible par n'importe qui : la politique de confidentialite
exigee par Google Play et l'App Store, la page de presentation, le contact.

## Pourquoi un depot separe du jeu

`UserNabil/piratesdice` porte le code du client, sa chaine de publication et ses
visuels de fiche. Il est public aujourd'hui, il n'a pas vocation a le rester.
GitHub Pages, lui, ne sert pas un depot prive sans abonnement — le site vivrait
donc ou le code doit pouvoir devenir prive. D'ou ce depot-ci : petit, public,
sans rien qui ait besoin d'etre cache.

## L'adresse, et pourquoi elle compte

    https://usernabil.github.io/piratesdice-site/privacy

Cette URL est ecrite a trois endroits qui ne se previennent pas entre eux :

  · la console Play        > Contenu de l'application > Politique de confidentialite
  · la fiche Play          > coordonnees, site web (`play_api.py --details`)
  · l'application          > `app/js/boot.js`, constante TERMS_URL

⚠️ La changer ici sans changer les trois autres donne un lien mort dans une
fiche en cours de revue — le motif de rejet qui a deja coute une soumission.
L'ancienne adresse `/piratesdice/privacy` redirige ici et doit continuer a le
faire : elle circule dans des versions deja installees.

## Publication

GitHub Pages, branche `main`, racine du depot. Pousser suffit.
