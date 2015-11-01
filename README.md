# Emu-Docs

This is an archive of emulator documentation and test ROMs to assist anyone understand the underlying architecture of multiple consoles.

# How to easily browse the archive

In the future, we are planning to create a [GitHub pages front-end](https://pages.github.com/) but for now, just execute the following command: `git clone --depth=1 https://github.com/Emu-Docs/Emu-Docs.git`

# Resources to Archive

http://emu-docs.org/

http://www.zophar.net/documents/

https://github.com/franckverrot/EmulationResources

# Documentation Guidelines

1. For documentation regarding specifics CPUs/chips, please put the appropriate documentation under "Shared Components". Inside the console's directory, create a relative symbolic link to the folder you created in "Shared Components".

2. Consoles should receive the full name "Playstation 2" instead of "PS2"

3. Test ROMs are welcome and should be placed under a folder called "test_roms"

4. Documentation about certain games or ROM hacking should be placed under a folder called "game_documentation"

5. Inside each folder, there should be a README.md describing the files in that directory
