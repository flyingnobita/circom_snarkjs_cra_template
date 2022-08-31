# Circom x Snarkjs x CRA Template

This repo serves as a template for a project based on [circom](https://github.com/iden3/circom), [Snarkjs](https://github.com/iden3/snarkjs), and React.

## Circuits

- circom v2.0.6 (packages/circuits)
  - last known `circom` version that is compatible with snarkjs@latest
- circomlib (packages/circuits)
- Power of Tau (power of 16) (packages/circuits/ptau)
- [snarkjs](https://github.com/iden3/snarkjs) (global package)
- gen.sh (packages/circuits)
  - script for compiling circuits from `circom` file and `input` file

## Frontend

- Create React App (packages/react-app)
  - with react-scripts v4.0.3 to overcome lack of polyfill in CRA/Webpack v5
- [styled components](https://github.com/styled-components/styled-components) (packages/react-app)

## Repo Management

- [Yarn Workspace](https://classic.yarnpkg.com/lang/en/docs/workspaces/) for managing as a monorepo
