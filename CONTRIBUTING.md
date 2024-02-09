All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.

Thanks for taking the time to contribute!
The following set of guidelines for contributing to this project and its packages are advised. Please remember these are just guidelines and not rules. Use your best judgement, and feel free to propose changes to this document in a pull request.

**Code of Conduct**
This project and everyone participating in it is governed by the project Code of Conduct (CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to github admin githubfinal@github.com.

**Package Conventions**
1. There are a few conventions that have developed over time around packages:
2. Packages that add one or more syntax highlighting grammars are named language-[language-name]
3. Language packages can add other things besides just a grammar. Many offer commonly-used snippets. Try not to add too much though.
4. Theme packages are split into two categories: UI and Syntax themes
5. UI themes are named [theme-name]-ui
6. Syntax themes are named [theme-name]-syntax
7. Often themes that are designed to work together are given the same root name, for example: one-dark-ui and one-dark-syntax
8. UI themes style everything outside of the editor pane — all of the green areas in the packages image above
9. Syntax themes style just the items inside the editor pane, mostly syntax highlighting
10. Packages that add autocomplete providers are named autocomplete-[what-they-autocomplete] — ex: autocomplete-css
