# Choosing a Git branching strategy for multi-account DevOps environments

Building solutions in AWS can be transformative. The modernization process implements robust software development lifecycles and DevOps practices that support automation across multiple environments. Choosing the right Git branching strategy for your organization helps you concisely communicate DevOps standards and best practices across development teams. Git branching can be simple in a single environment, but it can become confusing when applied across multiple environments, such as sandbox, development, testing, staging, and production environments. Having multiple environments increases the complexity of the DevOps implementation.

This guide provides visual diagrams of Git branching strategies that show how an organization can implement a multi-account DevOps process. Visual guides help teams understand how to merge their Git branching strategies with their DevOps practices. Using a standard branching model, like Gitflow, GitHub Flow, or Trunk, for managing the source code repository helps development teams align their work. These teams can also use standard Git training resources on the internet to understand and implement those models and strategies.

For DevOps best practices on AWS, review the DevOps Guidance in [AWS Well-Architected](https://docs.aws.amazon.com/wellarchitected/latest/devops-guidance/devops-guidance.html). As you review this guide, use due diligence to select the right branching strategy for your organization. Some strategies might fit your use case better than others.

The code in this repository helps you set up the following target architecture.

## [Trunk](/trunk/README.md)
![Trunk Branching Strategy](/trunk/trunk-diagram.png)

## [GitHub Flow](/github-flow/README.md)
![GitHub Flow Branching Strategy](/github-flow/githubflow-diagram.png)

## [Gitflow](/gitflow/README.md)
![Gitflow Branching Strategy](/gitflow/gitflow-diagram.png)

For prerequisites and instructions for using this AWS Prescriptive Guidance pattern, see [Pattern title](link to pattern on the external APG site).

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.