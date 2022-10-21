Github Actions Release Template
---

A template for github actions user to setup release pipelines.
The user should follow the pattern like:
1. Have one mainline branch (default `master`) that all the new changes would PR to
2. When ready to publish or deploy, checkout a new branch based on mainline with the name like `release/<release_date_or_meaningful_name>`
3. If there is a hotfix, firstly merge to mainline, then cherry pick to the release branch in use

