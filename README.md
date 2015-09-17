# IntelliJ/AndroidStudio's code style

IntelliJ IDE project's default settings for my project.

# How to install

* Create new project
* Quit IntelliJ
* Do following commands.

```sh
cd [IntelliJ Project HOME]
mkdir -p .idea/inspectionProfiles/
curl -L "https://raw.githubusercontent.com/shiraji/intellij-project-settings/master/codeStyleSettings.xml" > .idea/codeStyleSettings.xml
curl -L "https://raw.githubusercontent.com/shiraji/intellij-project-settings/master/inspectionProfiles/Project_Default.xml" > .idea/inspectionProfiles/Project_Default.xml
curl -L "https://raw.githubusercontent.com/shiraji/intellij-project-settings/master/inspectionProfiles/profiles_settings.xml" > .idea/inspectionProfiles/profiles_settings.xml
curl -L "https://raw.githubusercontent.com/shiraji/intellij-project-settings/master/inspectionProfiles/shiraji.xml" > .idea/inspectionProfiles/shiraji.xml
cat <<EOF >> .gitignore
.gradle
/local.properties
/.idea/workspace.xml
/.idea/libraries
/.idea/dictionaries
.DS_Store
/build
EOF
```

# See Also
https://github.com/cookpad/android-code-style

