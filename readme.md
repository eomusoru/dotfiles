#My dotfiles and preferences

When booting a new working station, we should set it up quickly. Dotfiles are great, but i've also listed my sublimetext preferences and packages etc...

## Step by step

- Install [those fonts](https://www.dropbox.com/s/sc3qqjm37bugjaa/fonts.zip?dl=0)
- Intall [iTerm](http://iterm2.com/)
- Then, [Sublime Text](http://www.sublimetext.com/3)
- Open iTerm and `cd`
- Symlink _subl_ : `ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" ~/bin/subl`
- Install [homebrew](http://brew.sh/)
- Install homebrew formulae : `./brew.sh`
- Execute the .osx in your terminal : `./.osx`
- Reboot
- Install [ohmyzsh](http://ohmyz.sh/) : `curl -L http://install.ohmyz.sh | sh`
- If needed, set the default shell to zsh : `chsh -s /bin/zsh`(http://cl.ly/image/2H2d3M1m2b35))
- Install [zsh-pure](https://github.com/sindresorhus/pure) (rtfm dude)
- Copy `.gitconfig`, `.gitignore` & `.zshrc` in your `~/`

## OS X Apps I couldn't live without

- [Spectacle](http://spectacleapp.com/)
- [1Password](https://agilebits.com/onepassword)
- [Sip](http://theolabrothers.com/sip/) / [Frank deLoupe](http://jumpzero.com/frank/)
- [Euclid](http://euclidapp.com/)
- [ImageOptim](https://imageoptim.com/fr.html)
- [Mou](http://25.io/mou/)
- [Name Changer](http://mrrsoftware.com/namechanger/)
- [Sketch](http://bohemiancoding.com/sketch/)
- [iTerm](http://iterm2.com/)
- [Sublime Text](http://www.sublimetext.com/3)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- My mouse's [drivers](http://steelseries.com/support/downloads)
- [VLC](https://www.videolan.org/vlc/)
- [Wunderlist](https://www.wunderlist.com/fr/)
- [Smooth mouse](http://smoothmouse.com/)

## Sublime text packages

After installing sublime text (3), you'll need to add it the [package control extension](https://sublime.wbond.net/installation), then install those great packages :

- [Theme Soda](https://github.com/buymeasoda/soda-theme/)
- [Alignment](http://wbond.net/sublime_packages/alignment)
- [PHP-Twig](https://github.com/Anomareh/PHP-Twig.tmbundle)
- [AutoFileName](https://github.com/BoundInCode/AutoFileName)
- [Sass](https://github.com/nathos/sass-textmate-bundle)
- [SCSS](https://github.com/MarioRicalde/SCSS.tmbundle)
- [Sass Snippets](https://github.com/sublimebrasil/sublime-snippets-sass)
- [LESS](https://sublime.wbond.net/packages/LESS)
- [Autoprefixer](https://github.com/sindresorhus/sublime-autoprefixer)
- [Bracket Highlighter](https://github.com/facelessuser/BracketHighlighter)
- [Color Highlighter](https://sublime.wbond.net/packages/Color%20Highlighter)
- [CSS3](https://github.com/y0ssar1an/CSS3)
- [CSS3 Snippets](https://github.com/joshnh/CSS-Snippets)
- [DocBlockr](https://github.com/spadgos/sublime-jsdocs)
- [SidebarGit](https://github.com/SublimeText/SideBarGit)
- [Emmet](https://github.com/sergeche/emmet-sublime)
- [Emmet CSS Snippets](https://p233.github.io/Emmet-Css-Snippets-for-Sublime-Text-2/)
- [Github Color Theme](https://github.com/AlexanderEkdahl/github-sublime-theme)
- [HTML5](https://github.com/mrmartineau/HTML5)
- [HTMLAttributes](https://github.com/agibsonsw/HTMLAttributes)
- [jQuery](https://github.com/SublimeText/jQuery)
- [JavascriptNext](https://github.com/Benvie/JavaScriptNext.tmLanguage)
- [JSHint](https://github.com/uipoet/sublime-jshint)
- [Markdown Editing](https://github.com/SublimeText-Markdown/MarkdownEditing)
- [Sublime linter](http://www.sublimelinter.com/en/latest/)
- [Trailing spaces](https://github.com/SublimeText/TrailingSpaces)

For the _Markdown Editing_ package, you'll need to edit the user settings for MultiMarkdown, GFM Markdown and Standard Markdown, adding those lines to the corresponfing files :

```
{
    "color_scheme": "Packages/MarkdownEditing/MarkdownEditor-Dark.tmTheme"
}
```
