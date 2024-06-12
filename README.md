
# Extensions and Configurations for VSCode

### How i can get my installed extensions
Execute that line in powershell
```
code --list-extensions | % { "code --install-extension $_" }
```

#### List of extensions:
- [better-comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [codesnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)
- [jsoncrack-vscode](https://marketplace.visualstudio.com/items?itemName=AykutSarac.jsoncrack-vscode)
- [aura-theme](https://marketplace.visualstudio.com/items?itemName=DaltonMenezes.aura-theme)
- [dart-code](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code)
- [flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)
- [gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [bloc](https://marketplace.visualstudio.com/items?itemName=FelixAngelov.bloc)
- [terminal](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal)
- [flutter-tree](https://marketplace.visualstudio.com/items?itemName=marcelovelasquez.flutter-tree)
- [quick-snippet](https://marketplace.visualstudio.com/items?itemName=mubasharjaved.quick-snippet)
- [awesome-flutter-snippets](https://marketplace.visualstudio.com/items?itemName=nash.awesome-flutter-snippets)
- [material-icon-theme](https://marketplace.visualstudio.com/items?itemName=pkief.material-icon-theme)
- [vscode-yaml](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
- [liveserver](https://marketplace.visualstudio.com/items?itemName=ritwickdey.liveserver)
- [flutter-riverpod-snippets](https://marketplace.visualstudio.com/items?itemName=robert-brunhage.flutter-riverpod-snippets)
- [errorlens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
- [npmLens](https://marketplace.visualstudio.com/items?itemName=Pilaton.vscode-npm-lens)

```
code --install-extension aaron-bond.better-comments
code --install-extension adpyke.codesnap
code --install-extension aykutsarac.jsoncrack-vscode
code --install-extension daltonmenezes.aura-theme
code --install-extension dart-code.dart-code
code --install-extension dart-code.flutter
code --install-extension eamodio.gitlens
code --install-extension felixangelov.bloc
code --install-extension formulahendry.terminal
code --install-extension marcelovelasquez.flutter-tree
code --install-extension mubasharjaved.quick-snippet
code --install-extension nash.awesome-flutter-snippets
code --install-extension pkief.material-icon-theme
code --install-extension redhat.vscode-yaml
code --install-extension ritwickdey.liveserver
code --install-extension robert-brunhage.flutter-riverpod-snippets
code --install-extension usernamehw.errorlens
code --install-extension Pilaton.vscode-npm-lens
```

### Profile Configurations
```
{
	"security.workspace.trust.enabled":  true,
	"explorer.compactFolders":  false,
	"explorer.fileNesting.enabled": true,
	"workbench.iconTheme":  "material-icon-theme",
	"workbench.colorTheme":  "Aura Dark",
	"editor.bracketPairColorization.enabled":  true,
	"editor.inlineSuggest.enabled":  true,
	"editor.formatOnSave":  true,
	"editor.formatOnPaste":  true,
	"editor.wordWrapColumn":  9000,
	"dart.previewFlutterUiGuides":  false,
	"dart.previewFlutterUiGuidesCustomTracking":  false,
	"dart.warnWhenEditingFilesOutsideWorkspace":  false,
	"dart.lineLength":  9000,
	"[dart]": {
		"editor.codeActionsOnSave": {
			"source.fixAll":  "always",
			"source.organizeImports":  "always"
		},
		"editor.selectionHighlight":  false,
		"editor.suggest.snippetsPreventQuickSuggestions":  false,
		"editor.suggestSelection":  "first",
		"editor.tabCompletion":  "onlySnippets",
		"editor.wordBasedSuggestions":  "allDocuments",
		"editor.wordWrap":  "off",
	},
}
```
