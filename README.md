# Sublime Setup


**Note**: for new machines, procced with [these steps](https://sublime.wbond.net/installation#st2)

## User Settings

    {
        "auto_complete_commit_on_tab ": true,
        "color_scheme": "Packages/Monokai Extended/Monokai Extended.tmTheme",
        "theme": "Afterglow-blue.sublime-theme",
        "detect_indentation": false,
        "detect_slow_plugins": false,
        "dictionary": "Packages/Language - Portuguese/Portuguese (Brazilian).dic",
        "draw_indent_guides": true,
        "ensure_newline_at_eof_on_save": true,
        "font_size": 14,
        "highlight_line": true,
        "tabs_small": true,
        "ignored_packages":
        [
            "Vintage"
        ],
        "indent_guide_options":
        [
            "draw_active"
        ],
        "rulers":
        [
            114
        ],
        "tab_size": 4,
        "translate_tabs_to_spaces": true,
        "trim_trailing_white_space_on_save": true,
        "word_wrap": true,
        "wrap_width": "auto"
    }


## Packages Installed

**Globals**

- [ApplySyntax](https://github.com/facelessuser/ApplySyntax)
- [Libraries from CDN](https://github.com/bwiklund/sublime-text-cdn)
- [Emmet](https://github.com/sergeche/emmet-sublime)
- [NetTuts+ Fetch](https://github.com/weslly/Nettuts-Fetch)
- [Placeholders](https://github.com/mrmartineau/Placeholders)
- [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter-for-ST2)

**Snippets**

- [JavaScript & NodeJS Snippets](https://github.com/zenorocha/sublime-javascript-snippets)
- [JavaScript Patterns Snippets](https://github.com/caiogondim/js-patterns-sublime-snippets/)
- [Angular Snippets](https://github.com/maxhoffmann/angular-snippets)
- [Mocha Snippets](https://github.com/jfromaniello/sublime-mocha-snippets)
- [Sass Snippets](https://github.com/sublimebrasil/sublime-snippets-sass/)
- [Ruby/Rails/Rspec/ERB Snippets](https://github.com/j10io/railsdev-sublime-snippets)

**Visual**

- [Scheme: Monokai Extended](https://github.com/jonschlinkert/sublime-monokai-extended)
- [Theme: Afterglow](https://github.com/YabataDesign/afterglow-theme)


## Sync Settings by Dropbox

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
    $ rm -r User
    $ ln -s ~/Dropbox/Sublime/User

> [Check this link](https://sublime.wbond.net/docs/syncing) for detailed information.

## License

[MIT License](http://vitorbritto.mit-license.org/) © Vitor Britto
