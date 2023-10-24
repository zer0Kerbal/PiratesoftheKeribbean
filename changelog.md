# Changelog  
  
| modName    | Pirates of the Keribbean (PotK) by GagaX                           |
| ---------- | ------------------------------------------------------------------ |
| license    | CC-BY-ND-4.0+ARR                                                   |
| author     | GagaX and zer0Kerbal                                               |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/218358-*/)  |
| github     | (https://github.com/zer0Kerbal/PiratesoftheKeribbean)              |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/PiratesoftheKeribbean) |
| spacedock  | (https://spacedock.info/mod/903)                                   |
| ckan       | PiratesoftheKeribbean                                              |

* 📌 Pinned
  * Dependencies:
    * [Rusty Star Shipyards (RSS)](https://www.curseforge.com/kerbal/ksp-mods/RustyStarShipyards)

## Version 0.9.99.1-prerelease - `<Merci vijay-varadarajan>` edition

* Released
  * 22 Oct 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 0.9.99.1

* Localize
  * French (Français)
    * Merci [vijay-varadarajan](https://github.com/vijay-varadarajan)

#### Localization 0.9.99.1

* Add
  * French (Français)
    * [fr-fr.cfg] v1.0.0.0
    * Merci [vijay-varadarajan](https://github.com/vijay-varadarajan)
* Update
  * add header, give credit
    * [fr-fr.cfg] v1.0.1.0
* closes #22 - French (Français) <fr-fr.cfg>
* updates #17 - Localization - Master

#### Documentation 0.9.99.1

* Update
  * [readme.md] v0.9.99.1
  * [Attributions.md] v1.0.1.0
  * [Localizations.md] v1.0.1.0

#### Status 0.9.99.1

* Issues
  * closes #41 - 0.9.99.1 Additional Tasks
  * closes #40 - Pirates of the Keribbean (PotK) 0.9.99.1-prerelease `<Merci vijay-varadarajan>` edition

---

## Version 0.9.99.0-adoption - `<Thank you GagaX>` edition

* Released
  * 16 Jul 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

* 📌 Pinned
  * Original twenty (20) parts plus three (3) new parts
  * Dependencies:
    * [Rusty Star Shipyards (RSS)](https://www.curseforge.com/kerbal/ksp-mods/RustyStarShipyards)
  * search for `potk` in editors to local all parts in this pact
  * <ghostparts.cfg> is provided for testing and is active.

### Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 0.9.99.0

* First of several staged updates
* Hard dependency is Rusty Star Shipyards (RSS)
  * provides agent, flags, and other common files
* New
  * Parts: three new parts
  * Compatibility: GimbalTrim

### Changes 0.9.99.0

#### Archival Releases

* closes #7 - Archival Releases
* closes #12 - 0.1.0.0-release - `<Archival Release>`
* closes #13 - 0.2.0.0-release - `<Archival Release>`

#### Parts 0.9.99.0

* NEW parts
  * ARRR-klaw 1.25m
  * Flag
    * medium
    * large
* Make flags antennas
* Make adapters fuel tanks
* Fix
  * missing textures (filenames didn't match pointers)
* Lint
  * too many changes to document
* Add
  * tags
  * header
  * Add/Update [DRAG_CUBE]
* Rename parts and part file
* closes #36 - Part Tags

#### Assets 0.9.99.0

* create Assets/ folder
* convert from mesh to MODEL
* decode from .dds --> png
* re-encode from .png --> bc3 .dds
* Rename and relocate
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* closes #9 - Part Asset Updates

#### Convert Sound Assets

* Convert
  * from `wav` to `ogg`
    * [sound_PoK_engine_engage.ogg]
    * [sound_PoK_engine.ogg]
    * [sound_PoK_engine_disengage.ogg]
* closes #37 - Convert Sound Assets

#### Compatibility 0.9.99.0

* Add
  * [GimbalTrim.cfg] v1.0.0.0

#### Config 0.9.99.0

* Add localized tags to parts
* Create
  * <PiratesoftheKeribbean.cfg> v1.0.0.0
    * adds localized tags to parts
* Create
  * [ghostparts.cfg]
  * this patch which will go away
* closes #10 - Create <PiratesoftheKeribbean.cfg>

#### Localization 0.9.99.0

* Create
  * Localization directory and contents
  * Create
    * Localization/
      * <en-us.cfg>
    * Translation guides
      * [en-us.cfg] v1.0.0.0
      * [readme.md] v2.1.2.1
      * [readme-ru.md] v1.0.0.0 - spasibo [evanisrael](https://github.com/evanisrael)
      * [quickstart.md] v1.0.2.0
      * [quickstart-ru.md] v1.0.2.0 - spasibo [evanisrael](https://github.com/evanisrael)
* closes #8 - Create Localization directory and contents
* closes #18 - English <en-us.cfg>
* closes #35 - Part Localization
* updates #17 - Localization - Master

#### GitHub Pages 0.9.99.0

* docs/
  * [`_config.yml`] v1.0.3.0
  * [404.md] v1.0.4.0
  * [Attribution.md] v1.0.9.0
  * [Disclaimer.md] v1.0.2.0
  * [Flags.md] v1.0.1.0
  * [LegalMumboJumbo.md] v1.0.6.0
  * [Localizations.md] v1.1.9.0
  * [ManualInstallation.md] v1.1.9.1
  * [Marketing.md] v1.0.3.0
  * [Notices.md] v1.0.2.0
  * [PartsCatalog.md] v1.1.4.3
  * [Why.md] v1.1.1.1
* Create
  * @thumbs/
  * add thumbnails
* closes #5 - Create GitHub Pages

#### Update License

* Updated License: CC BY-ND 4.0
  * was: CC BY-NC-ND 4.0
* closes #13 - Update License

#### Infrastructure 0.9.99.0

* [PiratesoftheKerribean.version]
  * update
  * remove
    * KSP_VERSION_MAX
* Create
  * HeroLogo.png
    * copy/convert to HeroLogo.jpg
  * All Rights Reserved
* closes #6 - Create HeroLogo.png
* closes #11 - Update License

### Status 0.9.99.0

* Issue
  * closes #1 - Pirates of the Keribbean (PotK) 0.9.99.0-adoption `<Thank you GagaX>` edition
  * closes #2 - 0.9.99.0 Create Legal Mumbo Jumbo
  * closes #3 - 0.9.99.0 Create Documentation
  * closes #4 - 0.9.99.0 Create Social Media Presence

---

## Version 0.2.0.0-release `<Archival>` edition

* Released
  * 29 Oct 2016
  * for Kerbal Space Program 1.2.2
  * by [GagaX](https://forum.kerbalspaceprogram.com/profile/57813-*/)

* added moar parts

### Status 0.2.0.0

* Issues
  * updates #7 - Archival Releases
  * closes #13 - 0.2.0.0-release - `<Archival Release>`

---

## Version 0.1.0.0-release `<Archival>` edition

* Released
  * 17 Aug 2016
  * for Kerbal Space Program 1.2
  * by [GagaX](https://forum.kerbalspaceprogram.com/profile/57813-*/)

* Creation by GagaX

### Status 0.1.0.0

* Issues
  * updates #7 - Archival Releases
  * closes #12 - 0.1.0.0-release - `<Archival Release>`

---