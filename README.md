Usage: appify-new [script.sh]

Just follow the prompts it gives you.

The script generates a macOS .app bundle from a bash script, and can handle custom app icons and basic, but extensible, dependency management. You can enter a list of Homebrew packages that will be checked for and installed if missing, but if you require additional setup you can point appify-new to any bash script. Custom install scripts will be run the first time the app bundle is executed, along with Homebrew package management, if any Homebrew packages were selected.

The only dependency is [Homebrew](brew.sh)
