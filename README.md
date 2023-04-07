# Profile Widget

A widget that shows the current progress of the profile creation of the user. The user should be able to see the missing tasks of a specific area and be able to mark them as done.

## Getting Started

These instructions will get you a copy of the client up and running on your local machine for development and testing purposes.

### Prerequisites

Installing Yarn 1.x is pretty straightforward using the installer package available from the [Yarn website](https://yarnpkg.com/getting-started/install).

This uses [Next.js](https://nextjs.org/) which will be installed when running `yarn install`. See configuration section below.

### Configuring your project

- Install requirements

```
yarn install
```

- Run server

```
yarn dev
```

This will run the application on `http://localhost:3000`.

## Testing the project

The folder \_\_tests\_\_ in the root directory has all the code to be able to test the project.

### Running test

#### Component testing

Component testing is defined as a software testing type, in which the testing is performed on each individual component separately without integrating with other components.

```
yarn test
```

it uses snapshot testing, to update the snapshot you may use the below command

```
test:u
```

#### E2E testing

End To End Testing is a software testing method that validates entire software from starting to the end along with its integration with external interfaces.

```
yarn playwright install
```

```
yarn test:e2e
```

it uses snapshot testing, to update the snapshot you may use the below command

```
test:ue2e
```
