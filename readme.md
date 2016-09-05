![](https://i.imgur.com/9ucpYgY.png)

## Installation

If you have [Go](https://golang.org/) installed, simply use `go get` to install
svnstreak.

`go get github.com/lasypig/svnstreak`

## Usage

You can use svnsteak to display the graph for any number of repositories.

`svnstreak path/to/repo1 path/to/repo2`

You can limit it to a specific user by specifying their email address.

`svnstreak -author user@example.org path/to/repo`

If you have a single directory with all your repositories, you can easily
include each repository.

`svnstreak -author user@example.org path/to/parent/*`

You can define an alias within your `.bashrc` file if you do not want to specify
a list of repository every time.

## Base on repository

[xudongzheng/gitstreak](https://github.com/xudongzheng/gitstreak) 

