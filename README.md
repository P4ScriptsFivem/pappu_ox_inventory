# Pappu Ox Inventory
A complete inventory system for FiveM, implementing items, weapons, shops, and more without any strict framework dependency.

## Features

- Server-side security ensures interactions with items, shops, and stashes are all validated.
- Logging for important events, such as purchases, item movement, and item creation or removal.
- Supports player-owned vehicles, licenses, and group systems implemented by frameworks.
- Fully synchronised, allowing multiple players to [access the same inventory](https://user-images.githubusercontent.com/65407488/230926091-c0033732-d293-48c9-9d62-6f6ae0a8a488.mp4).

## Preview
![Previewasdfsfsdfsdf](https://github.com/user-attachments/assets/afad24c1-a40b-4b49-bfd5-daa4a72dcafc)

## Supported frameworks

We do not guarantee compatibility or support for third-party resources.

- [ox_core](https://github.com/overextended/ox_core)
- [esx](https://github.com/esx-framework/esx_core)
- [qbox](https://github.com/Qbox-project/qbx_core)
- [nd_core](https://github.com/ND-Framework/ND_Core)

Maintenance Resources.
- [qbcore](https://github.com/qbcore-framework) 

## Items

- Inventory items are stored per-slot, with customisable metadata to support item uniqueness.
- Overrides default weapon-system with weapons as items.
- Weapon attachments and ammo system, including special ammo types.
- Durability, allowing items to be depleted or removed overtime.
- Internal item system provides secure and easy handling for item use effects.
- Compatibility with 3rd party framework item registration.

## Shops

- Restricted access based on groups and licenses.
- Support different currency for items (black money, poker chips, etc).

## Stashes

- Personal stashes, linking a stash with a specific identifier or creating per-player instances.
- Restricted access based on groups.
- Registration of new stashes from any resource.
- Containers allow access to stashes when using an item, like a paperbag or backpack.
- Access gloveboxes and trunks for any vehicle.
- Random item generation inside dumpsters and unowned vehicles.

## License
[GNU General Public License v3.0](LICENSE)

## Copyright
Copyright © 2024 Overextended <https://github.com/overextended>
