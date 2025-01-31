# CU Boulder Drupal 10 Project Template

All notable changes to this project will be documented in this file.

Repo : [GitHub Repository](https://github.com/CuBoulder/tiamat10-project-template)

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- ### Adds Trash module
  Gives Site Manager roles and up the ability to restore deleted content
  
  Includes:
  - `profile` => https://github.com/CuBoulder/tiamat10-profile/pull/251
  - `template` => https://github.com/CuBoulder/tiamat10-project-template/pull/71
  
  Resolves https://github.com/CuBoulder/tiamat10-profile/issues/250
---

- ### #65 Updates Linkit Contrib Module
  Updates Linkit from 6.1 to 7.0
  
  Resolves https://github.com/CuBoulder/tiamat10-project-template/issues/65
---

- ### Updating to Drupal 10.4 
  Update to Drupal 10.4 and Composer 2.8.5 
---

- ### Adds Article Syndication module
  The [Article Syndication](https://github.com/CuBoulder/ucb_article_syndication) module is needed in order to migrate the Today site and use the Campus News block with the migrated site (CuBoulder/ucb_campus_news#12). This update adds the module to `composer.json`.
  
  There is no sister PR in the profile because the module isn't enabled by default.
---

- ### Add Redis module
  Add current redis module to composer.
---

- ### Updates linter workflow
  Updates the linter workflow to use the new parent workflow in action-collection.
  
  CuBoulder/action-collection#7
  
  Sister PR in: All the things
---

- ### Update composer.json
  Add jsonapi_extras to accommodate ucb_focal_image_enable
  
  Resolves #57 
---

- ### Bumping composer version and compser allow required
  Bumping to latest composer version and adding in required libraries to the composer.json so that updates don't prompt every time to allow.  
---

- ### Add required module for mega menu
  Closes https://github.com/CuBoulder/tiamat-theme/issues/629.
  Adds the mega menu module to the composer json.
---

- ### Adds CU Boulder Styled Block custom module and updates block styles
  This update:
  - [new] Adds the new CU Boulder Styled Block custom module.
  - [new] Converts the Campus News block to a styled block, adding new style options to match our other blocks. CuBoulder/ucb_campus_news#6 CuBoulder/ucb_campus_news#9
  - [change] Refactors existing styled blocks to all extend the same Twig template with Twig inheritance.
  - [change] Corrects some indentation and other minor code style issues in affected block templates.
  
  Sister PR in: [ucb_campus_news](https://github.com/CuBoulder/ucb_campus_news/pull/10), [tiamat-theme](https://github.com/CuBoulder/tiamat-theme/pull/1209), [tiamat10-profile](https://github.com/CuBoulder/tiamat10-profile/pull/187)
---

- ### Adding in the ucb_drush_commands package
  Adding a new module that will serve as the repository for drush commands used main by the Ops team for maintenance of Web Express in production.  
---

- ### Remove Entity Embed Patch
  No longer needed as they reverted the change in the parent Entity module.  
  
  Also bumping PHP to 8.3 
---

- ### Adding in entity_embed patch 
  Adding in entity_embed patch.  
---

- ### Adds the CKEditor 5 Bootstrap Accordion module
  This update:
  - Adds the [CKEditor 5 Bootstrap Accordion](https://www.drupal.org/project/ckeditor5_bootstrap_accordion) module.
  - Adds the "Accordion" item to the CKEditor 5 toolbar for the WYSIWYG and Full HTML text formats.
  
  CuBoulder/tiamat10-profile#160
  
  Sister PR in: [tiamat10-profile](https://github.com/CuBoulder/tiamat10-profile/pull/161)
---

- ### Adds Rebuild Cache Access contrib module
  This new contrib module adds a "Rebuild Cache" option in the toolbar, accessible to architects and developers. **Use this sparingly and only as a last resort after you've tried everything else, such as clearing local browser caches. A cache rebuild is an administrative action that has temporary negative effects on the performance of the site.**
  
  CuBoulder/tiamat10-profile#147
  
  Sister PR in: [tiamat10-profile](https://github.com/CuBoulder/tiamat10-profile/pull/148)
---

- ### Project Template Updates
  Bumping versions of Composer ~~and PHP~~
  
  Adding in command to uninstall SAML on new install to make local development easier.  
---

- ### Adds captcha v3
  Adds captcha v3 to project template
  
  Includes:
  - `profile` => https://github.com/CuBoulder/tiamat10-profile/pull/138
  - `project-template` => https://github.com/CuBoulder/tiamat10-project-template/pull/45
  
  Resolves https://github.com/CuBoulder/tiamat-theme/issues/617
---

- ### Adding in SAML modules as well as Pantheon Domain Masking module
  New modules needed for Express in production on Pantheon.  
---

- ### Adds Anchor CKEditor5 Plugin
  Adds contrib module for handling CK5 Anchor tags
  
  Resolves https://github.com/CuBoulder/tiamat10-profile/issues/120
  Resolves https://github.com/CuBoulder/tiamat-theme/issues/502
  
  Includes:
  - `tiamat-profile` => https://github.com/CuBoulder/tiamat10-profile/pull/122
  - `project-template`=> https://github.com/CuBoulder/tiamat10-project-template/pull/43
---

- ### Removes the Devel contrib module
  CuBoulder/tiamat10-profile#108
  
  Sister PR in: [tiamat10-profile](https://github.com/CuBoulder/tiamat10-profile/pull/115)
---

- ### Adding in migrate_devel module for migration development
  Adding in migrate_devel module for migration development
---

- ### Adds `CHANGELOG.md`, workflows, and other housekeeping files
  Resolves CuBoulder/tiamat10-project-template#38
---
