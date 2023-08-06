# autodocker

This repo demonstrates some CI techniques.
First one is github workflow run. The workflow publish docker image on dorcker hub.

Second one is `pre-commit` tool which guards from too early commit into repository.
See https://pre-commit.com/

`pre-commit install` 😀

before you make a commit run

`pre-commit run --all-files`

as pre-commit is tool which modifies files, sometimes to pass you should run it twice
