# macOS Terminal-Hacks

This is a colleciton of terminal hacks I collected over the years.

```
# Show full file path in Finder

defaults write com.apple.finder _FXShowPosixPathInTitle -bool YES; killall Finder

# Make hidden apps in Dock actually hidden

defaults write com.apple.Dock showhidden -bool TRUE; killall Dock

# Eliminate the Dock Reveal Delay

defaults write com.apple.dock autohide-time-modifier -float 0.12;killall Dock
```
