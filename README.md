https://thecodingmachine.github.io/react-native-boilerplate/docs/BetaBuild


/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

 brew install node yarn cocoapods fastlane

cd iOS
pod install

sudo chown -R ${USER}:staff /usr/local/Cellar/

pod update hermes-engine --no-repo-update





