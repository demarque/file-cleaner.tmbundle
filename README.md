On save, remove blank lines at BOF & EOF, remove whitespace and add blank line at EOF.

### Installation Instructions

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/demarque/file-cleaner.tmbundle.git "file-cleaner.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

If you are using pre-release textmate2, the bundle should be installed in:

    mkdir -p ~/Library/Application\ Support/Avian/Bundles
    cd ~/Library/Application\ Support/Avian/Bundles
    git clone git://github.com/demarque/file-cleaner.tmbundle.git "file-cleaner.tmbundle"
