This changelog follows Semantic Versioning https://semver.org/

# 3.0.0

### Major

* Removed coverage script

### Minor

* Replaced test script with coverage script
* Added in --reporter=text to coverage
* Added testonly script

# 2.0.1

### Patch

* Updated npm deps
* Added missing coveralls and coverage scripts

# 2.0.0 (2019-07-24)

### Major

* Updated npm deps, breaking changes from @passport-next/eslint-config-passport-next causing
lint errors in some JSDoc cases @rwky

# 1.0.4 (2019-07-13)

### Patch

* Replaced make-node with nyc and coveralls in npm scripts @rwky

# 1.0.3 (2019-06-18)

### Patch

* Updated .github templates @rwky

# 1.0.2 (2019-06-18)

### Patch

* Removed comma-dangle config since it's included in the config @rwky
* Updated .npmignore and .gitignore @rwky
* Removed licenses in favour of licence from package.json @Rwky
* Cleaned up lint commands
* Removed deprecated test-cov and view-cov commands (TODO replace these) @rwky

# 1.0.1 (2019-06-15)

### Patch

* Added @passport-next/chai-passport-strategy dev dep @rwky

# 1.0.0 (2019-06-15)

### Major

Initial release @rwky
