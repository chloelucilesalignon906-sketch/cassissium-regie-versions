# Régie Cassissium : versions

Ce dépôt sert aux mises à jour automatiques de la Régie Cassissium.

- `derniere-version.json` : numéro de la dernière version et nom de son fichier.
- `Cassissium-Regie-Mise-a-jour-<version>.cassmaj` : mise à jour légère signée. Chaque régie (0.5 ou plus récente) la télécharge, vérifie sa signature, l'installe puis redémarre toute seule quand aucune séance n'est en cours.
- Les « releases » contiennent les installateurs complets (Windows et Mac).
- `companion/` : module Bitfocus Companion (`cassissium-regie-1.0.0.tgz`, à importer dans Companion › Modules) et page de boutons Stream Deck (`Cassissium-page-Stream-Deck.companionconfig`, à importer dans Companion › Import / Export).
