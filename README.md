# Item List

Please refer to the [documentation](https://sirrandoo.github.io/toolkit-utils/itemlist)
for instructions on how to set up your item list.

## Required Data Files for Automation

The following files in the `_data/` directory are required for the site to function properly:

### Core Store Data
- **`StoreItems.json`** - Item data for the store (items, animals, weapons)
- **`StoreIncidents.json`** - Event/incident data for purchase
- **`ShopExt.json`** - Extended shop data (traits, races/pawn kinds)

### Metadata Files
- **`itemdata.json`** - Item metadata (weights, categories, mods, etc.)
- **`eventdata.json`** - Event metadata (cooldowns, types, mods, etc.)
- **`commands.json`** - Available commands for the store
- **`modlist.json`** - List of mods being used

### Configuration Files
- **`language.yml`** - UI text and translations
- **`social.yml`** - Social media links and branding

All these files are automatically processed by Jekyll to build the item list site. Simply upload updated versions of these files and the site will rebuild automatically.
