First, install VimPlug (https://github.com/junegunn/vim-plug).

Next, go into .vimrc and run :PlugInstall.

(For VimTex, make sure you have a compatible PDF viewer for autocompile updates from VimTex, and edit those .vimrc options accordingly.)

I've redone this as a bare Git repo with the idea of cloning it
in the home directory, removing the need to manually move the tex snippets file to ~/.vim/Ultisnips.

I'm not sure if that will clash with the Plug-ins being installed
after the repo is cloned, since that might try to create the Ultisnips folder and overwrite the one the repo creates.
I don't know how that file-writing behavior works off the top of my head, so just keep it in mind when setting this and Vim plug-ins up on a device for the first time.
