# AWS Price List API Plugin for ChatGPT

This is a plugin for ChatGPT that allows users to manage and understand their AWS costs using the AWS Price List API.

# Overview 
AWS Users can install the plugin in their ChatGPT instance by providing the necessary authentication details and other required parameters.

Once the plugin is installed, users can query the AWS Price List API by sending a message to the ChatGPT instance, which will then use the plugin to make requests to the AWS Price List API.

Users can use the plugin to retrieve information about pricing offers, products, and terms, as well as filter and search for specific information using the API's query parameters.

With this information, users can better understand their AWS costs and optimize their usage to reduce costs where possible.

Users can also use the plugin to create automated alerts or reports based on specific pricing or usage criteria, such as alerts for when costs exceed a certain threshold or reports on cost trends over time. The plugin provides a convenient and accessible way for users to manage and understand their AWS costs, without requiring them to manually navigate the AWS console or write custom scripts.


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
