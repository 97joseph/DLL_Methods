# DLL_Methods

A simple DLL builder

We have 2 files (*.exe and *.dll) which are packed with PE protector. Most likely it's Guardant. What we need is:

- File have to be fully unpacked and functional ( reconstructed IAT, EAT etc... )
- All functions which are virtualized with VM macros must be transformed to real x86 code which can be later analyzed
- All encrypted strings should be decrypted
- Debug protector should be removed
