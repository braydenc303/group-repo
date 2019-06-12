# group-repo

experiments in conflict

## Todos

1. I will create the repo.

2. I will add Mike as a collaborator

3. I will set protection rules.

4. I will create a branch called initial, create the html file template with nothing in the body and push that up. Then create the pull request for Mike to merge it in.

    ```html
        <!DOCTYPE html>
        <html lang="en">
            <head>
                <meta charset="UTF-8">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <meta http-equiv="X-UA-Compatible" content="ie=edge">
                    <title>Document</title>
            </head>
            <body>
            </body>
        </html>
    ```

5. After he merges my branch in, Mike will pull that down and create a branch called "paragraphs" add the two paragraphs and push up his branch.

    ```html
        <div>
            <p>I want to make a mess of this.</p>
            <p>I don't even care if we fix it. I just want to see what happens when it breaks.</p>
        </div>
    ```

6. While he is making his changes, I will make some changes of my own on a branch called "heading", and add and commit them.

    ```html
        <h2>This is an experiment</h2>
    ```

    - Change the first paragraph to say, "I want to screw this up"

7. Mike will then do a git pull origin master to be safe.

8. Followed by a git add, git commit, and git push to his branch that he will then create a pull request for.

9. I will merge his changes in.

10. I will then go back to my branch and git pull origin master to be safe. This is where we should see a conflict to be resolved.

11. I will then resolve the conflict, save the file, and add, commit, and push the changes in my branch.

12. I can then create a pull request

13. Mike will merge that in

14. We can then both pull into our local master branches, create new branches, and delete old branches.
