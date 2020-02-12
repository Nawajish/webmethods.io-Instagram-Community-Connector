# webmethods.io-Instagram-Community-Connector
This is a simple Instagram connector that connects to and queries the Instagram Basic Display API. The following actions are supported:
1. Get information about the owner of the access_token.
2. Get the most recent media published by the owner of the access_token.
3. Get a list of recent comments on your media object.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This connector requires any [Node](https://nodejs.org/dist/) version between 4.x.x and 8 .14.

Note: If you have installed any other Node version on your system, you can:
1. Use tools to switch between different versions of Node

  - For Windows, use [nvm-windows](https://github.com/coreybutler/nvm-windows#installation--upgrades).
  
  - For Mac, use [homebrew](https://brew.sh/).
2. Build your app using your existing Node version and then transpile your code using a transpiler like [Babel](https://babeljs.io/).


Also, to use this connector. you must have [wmiocli](https://docs.webmethods.io/integration/developer_guide/connector_builder/#gsc.tab=0), webmethod.io's iPaaS Connector Builder CLI installed.

### Installing

1. Clone the repo `git clone https://github.com/Nawajish/webmethods.io-Instagram-Community-Connector.git`.
2. Run `npm install -g @webmethodsio/wmioclinpm install -g @webmethodsio/wmiocli`.
3. Login to your webmethods.io tenant using `wmio login`.
4. Execute `wmio init` to get started.
5. Finally, execute `wmio deploy` to deploy this connector to your tenant.

Once deployed, it’ll be automatically registered with webMethods.io Integration and will be available to you locally in the Connectors panel under the Services tab.

## Running the tests

To test, you can execute `wmio test`.

## Deployment

Execute `wmio deploy` to deploy this connector to your webmethods.io tenant. And `wmio unpublish` to unpublish the published connector app along with triggers and actions associated with the app.

## Built With
Node v8.14.0

## Contributors
See all contributors [here](https://github.com/Nawajish/webmethods.io-Instagram-Community-Connector/settings/access)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Srikanth Prathipati, Developer, Cloud Technologies, SoftwareAg


