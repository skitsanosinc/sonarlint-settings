# sonarlint-settings
Custom SonarLint rules for WebStorm to share across the team

Replacing your existing SonarLint rules is not exactly a straightforward operation, but it is not impossible, all that you need is to replace your `sonarlint.xml` file with the one you get from this repo. You can get it directly from [here](https://raw.githubusercontent.com/skitsanosinc/sonarlint-settings/main/sonarlint.xml)


On OSX:
```
~/Library/Application Support/JetBrains/{WEBSTORM_VERSION}/settingsRepository/repository
```

On Windows:
```
%homepath%\Application Data\JetBrains\{WEBSTORM_VERSION}\options
```

Replace `{WEBSTORM_VERSION}` with the version you want to use.

Keep your Webstorm closed while you change SonarLint rule set, or at least restart it when you are done.

## About SonarLint

SonarLint is a Free and Open Source IDE extension that identifies and helps you fix quality and security issues as you code. Like a spell checker, SonarLint squiggles flaws and provides real-time feedback and clear remediation guidance to deliver clean code from the get-go.

For more details, visit [https://www.sonarlint.org/](https://www.sonarlint.org/)
