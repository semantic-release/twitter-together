# twitter-together

> Submit tweets for [@SemanticRelease](https://twitter.com/SemanticRelease) using pull requests

To submit a new tweet, create a new `*.tweet` file in the [`tweets/`](`tweets/`) folder and send a pull request.

<kbd>[Create new tweet](../../new/master/?filename=tweets/<your-path>.tweet)</kbd>

## Example

Create a new file `tweets/hello-world.tweet` with the content

> Hello, world!

You can use subfolders, e.g. `tweets/2020/01/hello-world.tweet`, as long as the file is in the `tweets/` folder and has the `.tweet` file extension

## What to tweet

- Interesting usage/use-cases of semantic-release
- Tutorials/projects about release automation
- News about semantic-release and related projects
- Other items relevant to the semantic-release community

## Notes

- Only newly created files are handled. Deletions, updates or renames are ignored.
- `*.tweet` files will not be created for tweets you send out directly from twitter.com
- If you need to rename an existing tweet file, please do so locally using [`git mv old_filename new_filename`](https://help.github.com/en/articles/renaming-a-file-using-the-command-line), otherwise it may occur as deleted and added which would trigger a new tweet.

## Questions?

If you have any further questions or suggestions, please create an issue at [https://github.com/semantic-release/twitter-together/issues/new](https://github.com/semantic-release/twitter-together/issues/new)
