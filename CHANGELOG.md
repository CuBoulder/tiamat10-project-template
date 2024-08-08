# CU Boulder Drupal 10 Project Template

All notable changes to this project will be documented in this file.

Repo : [GitHub Repository](https://github.com/CuBoulder/tiamat10-project-template)

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

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
