# Choosing a Git branching strategy for multi-account DevOps environments

Building solutions in AWS can be transformative. The modernization process implements robust software development lifecycles and DevOps practices that support automation across multiple environments. Choosing the right Git branching strategy for your organization helps you concisely communicate DevOps standards and best practices across development teams. Git branching can be simple in a single environment, but it can become confusing when applied across multiple environments, such as sandbox, development, testing, staging, and production environments. Having multiple environments increases the complexity of the DevOps implementation.

This repository provides visual diagrams of Git branching strategies that show how an organization can implement a multi-account DevOps process. Visual guides help teams understand how to merge their Git branching strategies with their DevOps practices. Using a standard branching model, like Gitflow, GitHub Flow, or Trunk, for managing the source code repository helps development teams align their work. These teams can also use standard Git training resources on the internet to understand and implement those models and strategies.

This repository is part of an AWS documentation suite that is designed to help you choose and implement a Git branching strategy in your organization. For more information about choosing a strategy, see [Choosing a Git branching strategy for multi-account DevOps environments](https://docs.aws.amazon.com/prescriptive-guidance/latest/choosing-git-branch-approach/). For more information about implementation, see the following AWS Prescriptive Guidance patterns:
- [Implement a Trunk branching strategy for multi-account DevOps environments](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/implement-a-trunk-branching-strategy-for-multi-account-devops-environments.html)
- [Implement a GitHub Flow branching strategy for multi-account DevOps environments](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/implement-a-github-flow-branching-strategy-for-multi-account-devops-environments.html)
- [Implement a Gitflow branching strategy for multi-account DevOps environments](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/implement-a-gitflow-branching-strategy-for-multi-account-devops-environments.html)

The diagrams in this repository help you set up the following target architectures.

## [Trunk](/trunk/README.md)
![Trunk Branching Strategy](/trunk/trunk-diagram.png)

## [GitHub Flow](/github-flow/README.md)
![GitHub Flow Branching Strategy](/github-flow/githubflow-diagram.png)

## [Gitflow](/gitflow/README.md)
![Gitflow Branching Strategy](/gitflow/gitflow-diagram.png)


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.