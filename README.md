# monorepo-sample

This app is a proof-of-concept monorepo for splitting an app into 3 packages, onprem, cloud, and shared components. THe primary advantage is that the components provided in the `packages/ui-components` folder can be shared across both the onprem and cloud apps.

The sample is built following the example from https://github.com/react-workspaces/react-workspaces-playground and utilizes the following technologies
- react-workspaces
- lerna
- create-react-app

## Prerequisites
- Node v12
- Yarn 2

## Usage
To start cloud - `yarn start:cloud`

To start onprem - `yarn start:onprem`
