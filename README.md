# terraform-twingate-modules

This repository contains a collection of Terraform modules to manage Twingate resources across multiple cloud platforms. These modules are designed to simplify the integration of Twingate with cloud environments, enabling secure network connectivity for your applications.

> **Note**: This is an **alpha** repository and **not an official Twingate repo**. It is a community-supported project and may not be stable for production use.

## 🚀 Overview

This repo hosts a variety of Terraform modules tailored for use with Twingate, an identity-driven networking platform. The modules are organized by use cases and cloud providers, providing an easy way to integrate Twingate resources into your infrastructure.

### Modules Available

- **resource-app**: A module to define multiple Twingate resources that follow a common pattern, such as SaaS apps (e.g., Snowflake, GitHub, Jira, etc.).

## 📚 Documentation

Each module comes with its own documentation to explain how to configure and use the module. Please check the respective module's folder for detailed instructions and refer to examples/ for more specific examples on how to use.

For example:

- [**resource-app**](modules/resource-app/README.md): [Examples and usage](examples/resource-app/README.md)

## 🔧 Requirements

| Name        | Version |
| ----------- | ------- |
| `terraform` | >= 1.0  |
| `twingate`  | >= 3.0  |

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
