# Changelog

## v1.2.1 - 2026-09-03

- Added support for the Mortal Shell II build `++Sparta-Depot+Main+CL92935+1300-CL-0` while retaining the previously verified `CL92935+1279` build profile.
- Added a compact unsupported-game-version status indicator in the bottom bar.
- Added persistent GitHub and 3DM update links in the session panel.
- Preserved the existing Lock Health, Automatic Perfect Defense, Automatic Perfect Dodge, red-mark-only Dodge, Active Block, and Harden behavior.

## v1.2.0 - 2026-08-31

- Added support for the Mortal Shell II Week 1 build (`++Sparta-Depot+Main+CL92935+1279-CL-0`).
- Added health recovery for both the body and the currently active shell.
- Added an optional red-mark-focused Dodge mode that leaves confirmed guardable attacks untouched.
- Fixed remote-dispatch ownership during rebinding to reduce crash risk when a rebind overlaps menu transitions.
- Improved the combat-assistance interface while preserving the existing full-Dodge, Active Block, and Harden behavior.

## v1.1.2 - 2026-08-21

- Added automatic dodge coverage for additional radial and explosion attack routes.
- Improved hook lifecycle handling when supported area-damage sources are created, destroyed, or refreshed.
- Preserved defense-first handling for Active Block and Harden, with automatic dodge used for attacks those defense routes cannot handle.

## v1.1.1 - 2026-08-21

- Improved combat-assist recovery after equipment and player-object changes.
- Reduced cases where automatic defense or dodge required a manual memory rebind.

## v1.0.0 - 2026-08-20

- Initial public release.
- Added Automatic Perfect Defense for Active Block and Harden.
- Added Automatic Perfect Dodge for verified melee, projectile, and unblockable attack routes.
