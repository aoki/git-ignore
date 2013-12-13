git-ignore
==========

- Gitの.gitignoreを簡単に準備するためのgitサブコマンドです
- [gitignore.io](http://gitignore.io/)を利用しています
- 色々課題はあるので直していきたい

## Usage

```git ignore [-a|-i VALUE]```
- i: create a new .gitignore file
- a: add a list of ignore file-names to the .gitignore
- VALUE: 欲しい .gitignore のタイプ

### Create a new .gitignore for osx and java
``` git ignore -i osx,java```

作成されるリストはこんな感じ．

```
# Created by http://gitignore.io

### OSX ###
.DS_Store
.AppleDouble
.LSOverride
Icon


# Thumbnails
._*

# Files that might appear on external disk
.Spotlight-V100
.Trashes
# Created by http://gitignore.io

### Java ###
*.class

# Package Files #
*.jar
*.war
*.ear
```

### Add a list of ignore file-names for windows to the .gitignore
``` git ignore -a windows```
