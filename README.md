# Sublime Setup


**Note**: for new machines, procced with [these steps](https://sublime.wbond.net/installation#st2)

## User Settings

    {
        "auto_complete_commit_on_tab ": true,
        "theme": "Afterglow-blue.sublime-theme",
        "color_scheme": "Packages/Monokai Extended/Monokai Extended.tmTheme",
        "detect_indentation": false,
        "detect_slow_plugins": false,
        "dictionary": "Packages/Language - Portuguese/Portuguese (Brazilian).dic",
        "draw_indent_guides": true,
        "ensure_newline_at_eof_on_save": true,
        "font_size": 14,
        "highlight_line": true,
        "ignored_packages": ["Vintage"],
        "indent_guide_options": ["draw_active"],
        "rulers": "auto",
        "tab_size": 4,
        "tabs_small": true,
        "translate_tabs_to_spaces": true,
        "trim_trailing_white_space_on_save": true,
        "word_wrap": true,
        "wrap_width": "auto"
    }


## Packages Installed

**Globals**

- [Apply Syntax](https://github.com/facelessuser/ApplySyntax)
- [Libraries from CDN](https://github.com/bwiklund/sublime-text-cdn)
- [Emmet](https://github.com/sergeche/emmet-sublime)
- [Placeholders](https://github.com/mrmartineau/Placeholders)
- [Bracket Highlighter](https://github.com/facelessuser/BracketHighlighter)
- [Sublime REPL](https://github.com/wuub/SublimeREPL)

**Snippets**

- [JavaScript & NodeJS Snippets](https://github.com/zenorocha/sublime-javascript-snippets)
- [JavaScript Patterns Snippets](https://github.com/caiogondim/js-patterns-sublime-snippets/)
- [jQuery Snippets](https://github.com/SublimeText/jQuery)
- [Lazy Backbone](https://github.com/pwhisenhunt/Sublime-Text-2-Lazy-Backbone.js-Package)
- [NodeJS Snippets](https://github.com/tanepiper/SublimeText-Nodejs)
- [Mocha Snippets](https://github.com/jfromaniello/sublime-mocha-snippets)
- [Chai Snippets](https://github.com/pensive612/sublime-chai-full-completions)
- [Sass Snippets](https://github.com/sublimebrasil/sublime-snippets-sass/)
- [Ruby/Rails/Rspec/ERB Snippets](https://github.com/j10io/railsdev-sublime-snippets)

**Build**

- [Sublime Linter](https://github.com/SublimeLinter/SublimeLinter-for-ST2)
- [Sublime Minifier](https://github.com/bistory/Sublime-Minifier)
- [PHPcs](https://github.com/benmatselby/sublime-phpcs)

**Visual**

- [Scheme: Monokai Extended](https://github.com/jonschlinkert/sublime-monokai-extended)
- [Theme: Afterglow](https://github.com/YabataDesign/afterglow-theme)

**Experimental**

- [Sublime Erl](https://github.com/ostinelli/SublimErl)
- [Sublime Haskell](https://github.com/SublimeHaskell/SublimeHaskell)
- [Enchanced Clojure](https://github.com/Foxboron/SublimeClojure)

## Sync Settings by Dropbox

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
    $ rm -r User
    $ ln -s ~/Dropbox/Github/setup-subl/User

> [Check this link](https://sublime.wbond.net/docs/syncing) for detailed information.

## License

[MIT License](http://vitorbritto.mit-license.org/) © Vitor Britto
