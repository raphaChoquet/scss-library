# SCSS Library

Utilisation de la logique d'inuitcss et de ses composants: https://github.com/inuitcss

## Architecture dossier 

 + *root*
  - **1-settings/**
    * _settings.default.scss
    * _settings.responsive.scss
  - **2-tools/**
    * _tools.functions.scss 
    * _tools.mixins.scss 
    * _tools.responsive.scss
    * _tools.widths.scss
  - **3-generic/**
    * _generic.reset.scss
    * _generic.box-sizing.scss
    * _generic.normalize.scss
    * _generic.shared.scss
  - **4-base/**
    * _base.paragraphs.scss
    * _base.page.scss
    * _base.headings.scss
    * _base.lists.scss
    * _base.images.scss
  - **5-objects/**
    * _objects.list-ui.scss
    * _objects.tables.scss
    * _objects.pack.scss
    * _objects.media.scss
    * _objects.tabs.scss
    * _objects.flag.scss
    * _objects.box.scss
    * _objects.buttons.scss
    * _objects.list-block.scss
    * _objects.list-inline.scss
    * _objects.block.scss
    * _objects.layout.scss
    * _objects.list-bare.scss
  - **6-components/**
  - **7-trumps/**
    * _trumps.widths-responsive.scss
    * _trumps.spacing-responsive.scss
    * _trumps.spacing.scss
    * _trumps.clearfix.scss
    * _trumps.headings.scss
    * _trumps.print.scss
    * _trumps.widths.scss
  - main.scss


Détails: 
 - Settings: Variables globals, paramétre de l'ensemble du site, changement de configuration, etc.
 - Tools: Mixins et fonctions de l'ensemble du site.
 - Generic: faible spécification,  régles globals (e.g. resets).
 - Base: Éléments HTML déclassés (e.g. a {}, blockquote {}, address {}).
 - Objects: Objets, abstractions, et design patterns (e.g. .media {}).
 - Components: individuel, élément d'UI complet(e.g. .carousel {}). C'est la seule couche dont Inuit.scss n'utilise pas.
 - Trumps: Haute spécification, sélécteurs trés explicites. Overrides et helper classes (e.g. .hidden {})
