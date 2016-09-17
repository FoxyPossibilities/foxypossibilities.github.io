# Foxy Possibilities Website

This is the source to our website at FoxyPossibilities.com.  This website is
statically generated.

## Requirements

Install [Hugo](https://gohugo.io/).

## Getting the Source

Run the following to get the source of the website:

```sh
git clone --recursive https://github.com/FoxyPossibilities/foxypossibilities.github.io.git foxypossibilities
cd foxypossibilities
git remote set-url --push origin git@github.com:FoxyPossibilities/foxypossibilities.github.io.git
```

The `--recursive` option will automatically clone any git submodules, which is
how the themes are included.

The second command command sets it so that SSH is used for pushing.

## Running Locally

The following will build the site and run a local web server to host the site on
port `1313`:

```sh
hugo serve -D
```

Option `-w` is short for `--watch` and will watch content for changes and
rebuild the site when changes are detected.  This is on by default, so it is not
necessary to set on the command line.

Option `-D` is short for `--buildDrafts` and will include building content
marked as draft.

## Create Content

The following will create a new **tech** blog post:

```sh
hugo new tech/my-newest-post.md
```

This will create a new draft in `content/tech/my-new-post.md` which you can edit
with your favorite editor.
