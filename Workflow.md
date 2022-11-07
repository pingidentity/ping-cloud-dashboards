This repo is soft-pinned to PCB release. It means that ALL minor releases will take the dashboards from the same release branch. E.g. v1.17.0/v1.17.1/v1.17.2 will take the dashboards from v1.17-release-branch.
So to have some safety and QA review before pushing changes to prod we have the following workflow:

To do any changes only in current release:
1. Create new feature branch from current dev branch (like v1.17-dev-branch)
2. Push your changes to feature branch
3. Create MR from your feature branch to current dev branch
4. Get your MR merged (this needs dev approval)
5. Create MR from dev branch to release branch
6. Get your changes reviewed and tested by QA
7. Get your MR from dev to release branch merged (this needs QA approval)
8. Done. Your changes will be delivered to all current-release environments during their next full sync

To do any changes in many releases ( currently unavailable since 1.17 is a first release where this repo separated):
1. Check that monitoring have needed metrics in all releases where you want to push that changes
2. Create new feature branch from needed release dev branch
3. Push your changes to feature branch
4. Create MR from your feature branch to needed release dev branch
5. Get your MR merged (this needs dev approval)
6. Ask someone from maintainers to merge your changes to newer dev branches
7. Create MR from dev branch to release branch
8. Get your changes reviewed and tested by QA on dev branches
9. Get your MR from dev to release branch merged (this needs QA approval)
10. Ask someone from maintainers to merge your changes to newer releases
11. Done. Your changes will be delivered to all environments starting from selected release during their next full sync
