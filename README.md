# Robot-Framework code snippets generator README


## Features

Quick and easy advanced Robot-Framework code snippets for VS Code, you can use this to help speed up your development. For example, if you need to connect to SAP on the fly then we've got you covered! 

![Demo](resources/Robot-Snippets.gif)

Just start typing desired commands for example:

| Command  | Snippet |
| -------: | ------- |
| `Close SAP->` | SapGuiLibrary.Run Transaction \t /nex |
| `Save->` | SapGuiLibrary.Send Vkey \t F11 |
| `go back->` | SapGuiLibrary.Send Vkey \t F3 |
| `Start Video Recording->` | ScreenCapLibrary.Start Video Recording \t alisa=None \t name=recording \t fps=None \t size_percentage=1 \t embed=True \t embed_width=800px \t monitor=1 |

## Requirements

Extensions:
- Robot Framework Intellisense (tomiturtiainen.rf-intellisense)


## Extension Settings

Should be plug and play.

## Known Issues

Only works with ".robot" files.

## Release Notes

### 0.0.1

Initial release of robot-snippets, covering SapGuiLibrary and ScreenCapLibrary


-----------------------------------------------------------------------------------------------------------