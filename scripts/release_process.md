- update version in update.py
- run update.py from the scripts folder
- commit in dev with the version in the message
- merge dev in master and coverity_scan (and rebase them)
- push all branches (git push --all)
- create github release with the same semver tag as the changelog
