# auto-UEFI
**aufii** is a fast way to create UEFI-entries. An interactive tool to auto-generate UEFI-entries. **aufii** is interactive: while setting up your system you do not want to read man pages of commands you really seldomly need. **aufii** is a very simple bash script inviting you to add some more functionality and contribute to a tool which is made to JUST SAVE TIME.
## Usage
Simply run **aufii**. As it is very basic.

**aufii** works like this:
1. Asks for the EFI partition
2. Autodetects root partition 
3. Ask for swap partitions if system is using one
4. Autodetect microcode
5. Autodetect kernel version you use and 
6. AUTOMATICALLY CREATES THE NECESSARY COMMANDS FOR YOUR UEFI-ENTRIES with efibootmgr. 

You can check which devices will be used and wether the auto-composed commands are correct. 
aufii will create a small executable and if you need it will - execute it.

## Note
But carefully check the created commands, as wrong UEFI-entries will render a system unbootable. So you better have a live-system at hand when trying the tool late at night just for fun.

you are invited to add more functions and commit.
## Credits
- All credits goes to author [arl](https://github.com/de-arl/auto-UEFI-entry).
