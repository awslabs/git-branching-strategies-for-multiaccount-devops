## Git Branching Strategies for DevOps

## Summary
Clients that are implementing DevOps processes would benefit from a visual guide to assist them in understanding how a Git branching strategy can inform deployments to different environments with their DevOps processes. Using a standard workflow for managing the source code repository like GitFlow, GitHub Flow, or Trunk will assist development teams in aligning their work as a team.

This pattern provides a visual diagram to illustrate how a DevOps process following common git branching strategies could be implemented by an organization. AWS has provided official [AWS Well-Architected DevOps Guidance](https://docs.aws.amazon.com/wellarchitected/latest/devops-guidance/devops-guidance.html) and best practices and it is recommended that it is reviewed. This pattern includes pros and cons to using the each strategy, please use due diligence to select the right branching strategy for your organization as some strategies may fit your use case better than others. This pattern includes recommended tasks to perform at each step in the DevOps process.

The repository contains a diagrams for each strategy outlining the recommendations and can be used like a [punnett square](https://en.wikipedia.org/wiki/Punnett_square) to line up the branches on the horizontal axis with the AWS environments on the vertical axis to determine what actions to perform in each scenario.

The numbers in circles are to be used as a guide to help understand the order in which to follow the diagram with an example feature all the way to production deployment. 

The Draw.io diagramming files are included in this repository so the visual guides can be customized to your organization.

- [GitFlow](/gitflow/README.md)
- [GitHub Flow](/github-flow/README.md)
- [Trunk](/trunk/README.md)

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

