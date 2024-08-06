# My Latex Setup
Here I showcase my latex workflow. Lots of the software I use comes from a German PhD student, Gistle XX. I'll credit him where appropriate.

## The Setup

### My PC
I run arch Linux on my Lenovo ideapad.

I use arch because it's lightweight and I have full control over my setup and customisation. The learning curve is steep, but I was luckily already pretty comfortable in a terminal. I use gnome for my desktop environment, but I intend to switch to i3 at some point.

I like my ideapad because it has a touchscreen I can draw figures on in Inkscape (see below). The touchpad worked straight away in gnome.

### Terminal

I mainly work in bash, though have thought of switching to zsh. bash is all I need for the time being. I have a few aliases, see below. They help for easily opening latex docs at the start of lecture and commuting my latex doc and pdf at the end of work.


### Editor
Given I use arch, it's probably no surprise to here I use neovim (nvm) as my editor.

Similar to arch, neovim is lightweight and customisable. there's a learning curve and it takes time to get things setup to your liking, but I haven't looked back since switching to it.

Nvim also provides good support for plugins and custome commands I use to optimise my latex writing. You can view my whole config here XX.


### Latex in nvim

To use latex in nvim, I use the plugin vimtex XX, which allows continuous compilation of my pdfs on save, an obvious nice feature.

As for the lsp texlab XX gets the job done and is easy to setup.

My vimtex config is below



Most of these settings are not essential, and are just copied from Gistle or the vimtex docs XX.

My pdf viewer is zathura XX. Zathura has a nice dark mode - Dracula theme XX - and vim-like key-bindings. Most when you save your latex doc, vimtex compiles the pdf and 
