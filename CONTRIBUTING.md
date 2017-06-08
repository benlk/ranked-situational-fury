# If you would like to add a word:

1. Have a definition for it, with a citable link.
2. Have an idea of where in the list of ranked words it should go.

To add your word:

1. [Fork the repository on GitHub](https://help.github.com/articles/fork-a-repo/)
2. Edit `index.html` in two places:
	- add your word to the `ol` of words in the format `<li>word: short description</li>`
	- add your word and its definitino to the list of definitions, in the spot where it falls alphabetically
		- it is easiest to copy an existing word's definition, and then edit that
		- make sure that your link is a link
		- make sure that the `label for=""` attribute matches the `input id=""` attribute: these must match so that the margin notes work on narrower screens.
		- hi yes you need to know some HTML, sorry :sad:
5. [Open a pull request](https://help.github.com/articles/creating-a-pull-request/) between your fork and this repository, noting the word and the reason you put it where you did in the list.

# If you would like to rearrange the order:

[Make an issue](https://help.github.com/articles/creating-an-issue/) on this repository, noting:

- which words you would like to reorder
- why you would like to reorder them

# If you have something else:

Fork the repo, submit a pull request, and we'll talk about it. Or open an issue, and we'll talk about it.
