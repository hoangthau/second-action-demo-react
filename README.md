# Actions for React app
- Add action event are on: [push, workflow_dispatch]
- Two jobs: test and deploy
- Define some steps to checkout code, setup node, install deps, run tests, build projects, upload artifacts,...
- Output github context
- Add event on PR opened: run test, build and deloy
- Add event on specific branch ex `feat/test`
