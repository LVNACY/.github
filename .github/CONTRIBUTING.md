# Contributing

## Workflow

1. Fork and clone this repository.
2. Create a new branch in your fork based off the **main** branch.
3. Make your changes.
4. Commit your changes, and push them.
5. Submit a pull request!

For details regarding this workflow, see [WORKFLOW.md][workflow].

## Contributing to the code

**The issue tracker is only for issue reporting. For proposals/suggestions,
please begin a new discussion using the suggestions form in the suggestions
category. If you have a question, you can find us in our
[Discord Server][discord server]**.

To contribute to this repository, begin by creating a new fork of the
repository and submit a pull request. [ESLint] is highly recommended; install
it in your text editor or IDE and routinely run the linting script to ensure your
code will pass any GitHub Actions set to run when you submit a pull request.

### LVNACY project concepts guidelines

There are a number of guidelines considered when reviewing pull requests.
Guidelines are fairly generalized; as such, these are not hard and fast rules,
but rather ideas by which to write and operate by:

- 	Each project is a specific concept and works to provide resources for
	exploration and organization for those interested in Art and Design, or to
	pursue an idea or concept for the sake of learning and building. If you have
	an idea that is related to a project and unsure if it fits, let's have a
	chat about it. New projects can be given lift at any time.  

- 	With regard to any discord-bot related development, everything should be
	shard compliant. If code you write and submit would break when sharding,
	break other things from supporting sharding, or is incompatible with
	sharding, then you will need to think of a way to make it work with sharding
	before your submission/pull request will be accepted and merged.

- 	**most** projects will follow [OOP paradigms][oop paradigms] and generally
	rely on behaviour over state where possible. This generally helps methods
	be predictable, keeps the codebase simple and understandable, reduces code
	duplication through abstraction, and leads to efficiency and scalability.

- 	Projects written in JS/TypeScript are written as [ES Modules][esm]. The
	package.json will include a `type` field set to `modules`. Code submissions
	should follow ESM syntax whether they're written in JavaScript or TypeScript.

- 	Everything should follow our ESLint rules as closely as possible, and should
	pass lint tests even if you must disable a rule for a single line.

If you questions whether or not your code or ideas adhere to these guidelines,
please find us in the [Discord Server][discord server] and ask away!

These guidelines have been modified from the contributing guidelines in use
by the [Sapphire.js][sapphire] team.

<!-- Link Dump -->

[discord server]: https://discord.gg/M8Aqgr3ftC
[eslint]: https://eslint.org/
[node.js]: https://nodejs.org/en/download/
[yarn]: https://yarnpkg.com/getting-started/install
[oop paradigms]: https://www.educative.io/blog/object-oriented-programming
[esm]: https://nodejs.org/api/esm.html
[sapphire]: https://github.com/sapphiredev/.github/blob/main/.github/CONTRIBUTING.md
[workflow]: https://github.com/LVNACY/.github/blob/main/.github/WORKFLOW.md