# IntelliJ/AndroidStudio's code style

Code style for IntelliJ-base IDE project.

# Installation

When create new project, do following commands.

```sh
cd [IntelliJ Project HOME]
curl -L "https://raw.githubusercontent.com/shiraji/intellij-codestyle/master/codeStyleSettings.xml" > .idea/codeStyleSettings.xml
cat <<EOF > .gitignore
.idea/*
!.idea/codeStyleSettings.xml
EOF
```

# See Also
https://github.com/cookpad/android-code-style

