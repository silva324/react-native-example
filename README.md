https://thecodingmachine.github.io/react-native-boilerplate/docs/BetaBuild

Install
```console
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install node yarn cocoapods fastlane
```

Go to react-native project folder:
```console
npm install
cd ios
pod install
cd ..
npm run ios
```

If error during the 'pod install', try this:
```console
sudo chown -R ${USER}:staff /usr/local/Cellar/
pod update hermes-engine --no-repo-update
```






cd ios
fastlane init