# Semantic Commit Messages

I saw this [post](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716), love, copy / paste and change some little things to use in my personal projects!

`See how a minor change to your commit message style can make you a better programmer.`

Format: `<type>(optional <scope>): <description>`

`<type>` type of the commit
`<scope>` impacted scope
`<description>` short description about the commit

## Example

```
feat(screen x): add new btn in the x screen
^----^---------^----------------------------^
|    |         |
|    |         +--> Description in present tense.
|    |
|    +----> Impacted by this commit.
|
+--> Commit Type: chore, docs, feat, fix, refactor, style, or test.
```

Types description:

- `feat`: (new feature)
- `fix`: (bug fix)
- `refactor`: (refactoring production code. renaming a variable)
- `chore`: (updating grunt tasks etc; no production code change)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `docs`: (changes to the documentation)
- `test`: (adding missing tests, refactoring tests; no production code change)

Scope description examples:

- `forms`: (all forms was impacted)
- `dashboard`: (only dashboard was impacted)
- `resquests`: (the requests was impacted)

References:

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
