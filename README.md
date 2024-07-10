# Terraform WordPress Infrastructure

This project demonstrates how to use Terraform to create a basic infrastructure on AWS for hosting a WordPress service.

## Prerequisites

Before you begin, make sure you have the following:

- An AWS account
- Terraform installed on your local machine

## Getting Started

1. Clone this repository to your local machine.
2. Navigate to the project directory: `cd wp-terraform`.
3. Initialize Terraform: `terraform init`.
4. Configure your AWS credentials by setting the environment variables `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`.
5. Modify the `variables.tf` file to customize the infrastructure settings.
6. Run `terraform plan` to see the execution plan.
7. Run `terraform apply` to create the infrastructure.
8. Once the infrastructure is created, you can access your WordPress service by visiting the provided URL.

## Cleaning Up

To clean up and delete the infrastructure, run `terraform destroy`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
