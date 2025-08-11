# argus-artifacts

> ⚠️ **Note:** Parts of this README were generated using AI and may contain inaccuracies. Please verify the information before use.

## Overview

The argus-artifacts repository contains GitHub Actions and infrastructure configurations for managing application deployment stacks. This repository serves as a collection of reusable components for CI/CD workflows.

## Components

### GitHub Actions

- **create-stack**: Creates a platform stack for an application in a specified environment
- **delete-stack**: Deletes a platform stack for an application in a specified environment
- **get-app-info**: Retrieves application information
- **wait-for-deployment**: Waits for a deployment to complete
- **shared**: Common utilities used by other actions

### Infrastructure Configurations

- **ECR Settings**: AWS Elastic Container Registry policies and lifecycle configurations

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Security

If you believe you have found a security issue, please see our [security policy](SECURITY.md) for information on how to report it.

## Code of Conduct

This project adheres to the Contributor Covenant [code of conduct](https://github.com/chanzuckerberg/.github/blob/master/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. 
Please report unacceptable behavior to [opensource@chanzuckerberg.com](mailto:opensource@chanzuckerberg.com).