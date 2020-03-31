# rafay-gitlab-ci

This is a sample Gitlab CI that can be used with Rafay CLI RCTL.

## Getting Started

You will have to setup the following environment variables in your gitlab project.

```
RCTL_API_KEY
RCTL_API_SECRET
```

This example shows a 4 stage pipeline. 

```
build
deploy
test
cleanup
```

It can be modified based on your needs.

