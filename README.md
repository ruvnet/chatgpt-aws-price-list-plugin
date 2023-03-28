# AWS Price List API Plugin for ChatGPT

This is a plugin for ChatGPT that allows users to manage and understand their AWS costs using the AWS Price List API.

## Installation

To install the plugin, follow these steps:

1. Create a ChatGPT instance.
2. Create an AWS account and generate API credentials.
3. Clone the repository or download the ZIP file.
4. Update the `auth` section of the `manifest.yml` file with your AWS API credentials.
5. Update the `api.url` field in the `manifest.yml` file to match the AWS Price List API endpoint for your region.
6. Deploy the plugin to your ChatGPT instance.

## Usage

To use the plugin, send a message to your ChatGPT instance with a query for the AWS Price List API. The plugin will automatically make the necessary requests to the API and return the results.

For more information on the available API endpoints and query parameters, refer to the plugin's OpenAPI specification in the `openapi.yml` file.

## Contributing

Contributions are welcome! To contribute to the plugin, follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
