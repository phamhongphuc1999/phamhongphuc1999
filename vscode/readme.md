## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Food/Birthday%20Cake.png" alt="Birthday Cake" width="25" height="25" /> My VSCode config

-   After one time <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Bomb.png" alt="Bomb" width="25" height="25" /> fixing my laptop and losing all the data, i realized saving vscode config is very important. But, i seemingly don't like [setting-sync](https://code.visualstudio.com/docs/editor/settings-sync) so i decided to export my vscode config as json file, and in the future, i can recover it if necessary. However, in this way, if i change my vscode config, i must backup my data again manually, so i don't encourage follow my way, you should use [setting-sync](https://code.visualstudio.com/docs/editor/settings-sync).

## Get <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Lady%20Beetle.png" alt="Lady Beetle" width="25" height="25" /> extension list and setting <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Baby%20Chick.png" alt="Baby Chick" width="25" height="25" />

#### 1. Get extension list

```shell
code --list-extensions | xargs -L 1 echo code --install-extension
```

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Honeybee.png" alt="Honeybee" width="25" height="25" /> Recovery

#### 1. Recover setting.json

-   Copy and parse setting.json to new vscode setting.json(Command + P and enter: Preferences: Open User Settings(JSON))

#### 2. Recover extensions

-   Open terminal and run shell file

```shell
./extension.sh
```
