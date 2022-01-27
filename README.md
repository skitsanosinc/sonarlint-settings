# sonarlint-settings
Custom SonarLint rules for WebStorm to share across the team

Replacing your existing SonarLint rules is not exactly a straight forward operation, but it is not impossible. all that you need is to replace your `sonarlint.xml` file with the one you get from this repo.


On OSX:
```
~/Library/Application Support/JetBrains/{WEBSTORM_VERSION}/settingsRepository/repository
```

On Windows:
```
%homepath%\Application Data\JetBrains\{WEBSTORM_VERSION}\options
```

Replace `{WEBSTORM_VERSION}` with the version you want to use.
