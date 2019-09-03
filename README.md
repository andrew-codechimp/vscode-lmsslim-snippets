# LMS Slim Snippets

Snippets for Logitech Media Server dev, provides both perl and html snippets to help with common slim dev tasks.

## Installation
Type `cmd + shift + p` to launch command palette and choose `Extensions: Install Extension`. Search for `lms slim snippets` and install.

Installation link (if your are not seeing this from inside VSCode): https://marketplace.visualstudio.com/items?itemName=codechimp.lmsslim-snippets#overview


## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Slim Perl
| Trigger           | Content |
| -------           | ------- |
| `slimloguse⇥`     | import slim log |
| `slimloginit⇥`    | init the log |
| `slimlogdebug⇥`   | create a debug log |
| `slimloginfo⇥`    | create an info log |
| `slimlogwarn⇥`    | create a warning log |
| `slimlogerror⇥`   | create an error log |


### Slim HTML
| Trigger                       | Content |
| -------                       | ------- |
| `slimsettingtitle⇥`           | create a title wrapper |
| `slimsettinginputtext⇥`       | create a text input wrapper |
| `slimsettinginputcheckbox⇥`   | creates a checkbox wrapper |

### Perl
| Trigger         | Content |
| -------         | ------- |
| `if⇥`           | creates an if block |
| `for⇥`          | creates a for block |
| `argsclass⇥`    | creates class method arguments |
| `argsobject⇥`   | creates object arguments |

## Modifying
If you want to add/modify snippets you can find this extension in  
* Windows %USERPROFILE%\\.vscode\\extensions\\codechimp.lmsslim-snippets-VERSION
* macOS ~/.vscode/extensions/codechimp.lmsslim-snippets-VERSION
* Linux ~/.vscode/extensions/lcodechimp.lmsslim-snippets-VERSION

Within the snippets folder modify the appropriate json file and reload VSCode to pick up the changes.

If your change is useful to others then consider a pull request to get it added to this extension, you can find the source repository at https://github.com/codechimp-org/vscode-lmsslim-snippets

## Release Notes

### 1.0.0
Initial release
