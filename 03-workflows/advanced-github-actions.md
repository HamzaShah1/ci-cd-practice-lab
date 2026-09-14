you can use conditions, and expressions  in your workflow

conditions:
-   name: Run Tests
    run: python -m unittest discover
    if: success()


expressions:

-   name: Print branch name
    run: echo The branch name is ${{github.ref}}

Matrix builds:

- you can use matrix builds to run multiple job configurations in parallel
- its useful for testing across multiple environments (eg: python versions, operating systems, etc.)

