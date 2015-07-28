# IntelliJ/AndroidStudio's code style

IntelliJ IDE project's default settings for my project.

# How to install

Create new project, and then do following commands.

```sh
cd [IntelliJ Project HOME]
mkdir -p .idea/inspectionProfiles/
curl -L "https://raw.githubusercontent.com/shiraji/intellij-project-settings/master/codeStyleSettings.xml" > .idea/codeStyleSettings.xml
curl -L "https://raw.githubusercontent.com/shiraji/intellij-project-settings/master/inspectionProfiles/Project_Default.xml" > .idea/inspectionProfiles/Project_Default.xml
curl -L "https://raw.githubusercontent.com/shiraji/intellij-project-settings/master/inspectionProfiles/profiles_settings.xml" > .idea/inspectionProfiles/profiles_settings.xml
curl -L "https://raw.githubusercontent.com/shiraji/intellij-project-settings/master/inspectionProfiles/shiraji.xml" > .idea/inspectionProfiles/shiraji.xml
cat <<EOF >> .gitignore
.idea/*
!.idea/codeStyleSettings.xml
!.idea/inspectionProfiles
EOF
```

# See Also
https://github.com/cookpad/android-code-style

