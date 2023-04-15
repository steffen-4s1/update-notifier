# Update Notifier

With this repository I get informed about updates of different projects with the help of the Renovate Bot. For this purpose, dummy files are available for the respective projects in the form of a `Dockerfile` or `package.json`.

## How does it works

If there is an update, the Renovate Bot makes a pull request and assigns it to me. As soon as I have taken note of the update, I merge the pull request.

## Advantages of this approach

- I see the entire changelog in the pull request for most projects and don't have to navigate to the specific project page.
- If I don't get to look at a pull request and there is another update for a project, the Renovate Bot will update the pull request and list the changelog for both versions.
- I have all the projects that are relevant to me in one place and don't have to subscribe to releases for each project individually.

## Notes

[Forgejo versioning](https://github.com/renovatebot/renovate/discussions/20561)
