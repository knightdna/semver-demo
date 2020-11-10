# semver-demo
Semantic versioning demo

## Prerequisites
- NPM
- Git

## Steps
- Perform any code changes which is preferred to be done in a specific feature/fix branch
- Commit the code and follow the conventional commit specification 
- Once the code is merged to master branch (typically after merging a pull request), execute `npm run release`
- It will automatically bump the version, update the changelog, and perform git tag
- We can run `npm run release` together with the other standard release procedure (e.g. serverless deployment, docker image packaging and push, deployment to kubernetes cluster, etc.), which can also be done in any CI/CD automated pipeline

## References
- https://semver.org
- https://www.conventionalcommits.org
