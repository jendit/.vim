# .vim
My vim settings.

When cloning the project, it will create a .vim folder to hold all files and informations.
Vim needs the .vimrc file in the home folder to recognize it on startup.
As I wanted to stick the .vimrc file within the .vim folder for easier github sync,
here is a way to simply create a link in the home folder leading vim to it.

linux:
ln -s source_file target_file
example:
ln -s .vim/.vimrc .vimrc

This creates a link called .vimrc that leads to .vim/.vimrc

