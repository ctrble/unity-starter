# Unity Starter Template

Unity game [repo starter template](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) with [LFS support](https://docs.github.com/en/free-pro-team@latest/github/managing-large-files/about-git-large-file-storage) for various file types.

## Installation

1. Use this repo as a GitHub starter template
2. Clone it locally, rename the directory if needed
3. Create a new Unity project, saving it in the cloned repo directory
4. Move `.gitignoreUNITY` to the root of the new Unity project directory
5. Rename `.gitignoreUNITY` to `.gitignore`

## Usage

Your project structure will look something like this:

```
.git
.gitattributes
.gitignore
LICENSE
README.md
/[Unity project]
  .gitignore (formerly .gitignoreUNITY)
  ...[other Unity project stuff]
```

Feel free to update this README, the root `.gitignore`, and `.gitattributes` to suit your needs.

The root `.gitignore` has references for a couple directories that I usually create. These are also optional (obviously), create them if you want:

```
/Builds (game builds, already ignored)
/Media (assorted game-related images and videos, uncomment to ignore)
```

GLHF!
