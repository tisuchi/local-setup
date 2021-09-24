# VS Code

## Extensions
Here is the list of the extension that I use-

- [Auto Close Tab](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [Auto Complete Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Best Light Themes Pack](https://marketplace.visualstudio.com/items?itemName=thegeoffstevens.best-light-themes-pack)
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [Better PHPUnit](https://marketplace.visualstudio.com/items?itemName=calebporzio.better-phpunit)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Composer](https://marketplace.visualstudio.com/items?itemName=ikappas.composer)
- [Coverage Gutters](https://marketplace.visualstudio.com/items?itemName=ryanluker.vscode-coverage-gutters)
- [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [File Utils](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils)
- [Getter/Setter Generator](https://marketplace.visualstudio.com/items?itemName=Gabsii.getter-setter-generator)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [GitHub Plus Theme](https://marketplace.visualstudio.com/items?itemName=thenikso.github-plus-theme)
- [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)
- [GitLab Workflow](https://marketplace.visualstudio.com/items?itemName=GitLab.gitlab-workflow)
- [GitLens Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [htmltagwrap](https://marketplace.visualstudio.com/items?itemName=bradgashler.htmltagwrap)
- [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
- [Laravel Artisan](https://marketplace.visualstudio.com/items?itemName=ryannaddy.laravel-artisan)
- [Laravel Blade formatter](https://marketplace.visualstudio.com/items?itemName=shufo.vscode-blade-formatter)
- [Laravel Blade Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel-blade)
- [Laravel Extra Intellisense](https://marketplace.visualstudio.com/items?itemName=amiralizadeh9480.laravel-extra-intellisense)
- [Laravel Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel5-snippets)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
- [Mermaid Markdown Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=bpruitt-goddard.mermaid-markdown-syntax-highlighting)
- [PHP Class Generator](https://marketplace.visualstudio.com/items?itemName=damianbal.vs-phpclassgen)
- [PHP Constructor](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-constructor)
- [PHP Debug](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-debug)
- [PHP Getters & Setters](https://marketplace.visualstudio.com/items?itemName=phproberto.vscode-php-getters-setters)
- [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)
- [PHP Namespace Resolver](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-namespace-resolver)
- [PHP Static Analysis](https://marketplace.visualstudio.com/items?itemName=breezelin.phpstan)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Rainbow Brackets](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets)
- [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
- [Random Everything](https://marketplace.visualstudio.com/items?itemName=helixquar.randomeverything)
- [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
- [ShellCheck](https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck)
- [snippet-creator](https://marketplace.visualstudio.com/items?itemName=nikitaKunevich.snippet-creator)
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [Text Manipulator](https://marketplace.visualstudio.com/items?itemName=adamwalzer.string-converter)
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
- [Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [vscode-phpstan](https://marketplace.visualstudio.com/items?itemName=calsmurf2904.vscode-phpstan)
- [PHP Formatter](https://marketplace.visualstudio.com/items?itemName=Sophisticode.php-formatter)

## VIM
I am a big fan of [VIM](https://www.vim.org/). I am using vim in VS Code. Beside regular commands of VIM, I use some customized command. Here is a sample-

```json
    /**
    * VIM Settings
    **/
    "vim.insertModeKeyBindings": [
        {
            "before": ["j", "j"],
            "after": ["<Esc>"]
        },
    ],
    "vim.normalModeKeyBindings": [
        {
            "before": ["<tab>"],
            "commands": ["workbench.action.nextEditor"],
        },
        {
            "before": ["<S-tab"],
            "commands": ["workbench.action.previousEditor"]
        }
    ],
    "vim.normalModeKeyBindingsNonRecursive": [
        {
            "before": ["<leader>", "w"],
            "commands": ["workbench.action.splitEditor"]
        },
        {
            "before": ["<leader>", "s"],
            "after": ["_"]
        },
        {
            "before": ["<leader>", "e"],
            "after": ["$"]
        },
    ],
    "vim.leader": "space",
```

[Find full settings.json](code-editors/vs-code/settings.json)
