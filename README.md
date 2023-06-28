# `git draft-commit`

This script lets you draft a commit as you work. For example, if you intend
to make a commit that resolves an issue, you can draft the following.

```gitcommit
Fix issue #1
```

And then, once you've completed your work, you can "publish" your draft. Your
editor will be opened once more to allow you to do the final touches to your
draft.

```gitcommit
Do thing that unbreaks stuff

I did a thing.

Fixes issue #1
```

## Usage

```shell
# Open your editor to draft a commit message
git draft-commit

# Complete your commit
# This works by calling `git commit -F=path/to/draft`
git draft-commit --publish  # short option is -p
```

## Installation

Download the script and install it somewhere in `PATH`.
