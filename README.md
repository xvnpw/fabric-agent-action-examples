# Fabric Agent Action Examples

This repo provides examples of how to effectively use [fabric-agent-action](https://github.com/xvnpw/fabric-agent-action).

GitHub Action designed to automate complex workflows 
through agent based approach. Powered by Fabric Patterns and built with lang graph, this action leverages the capabilities of Large Language Models (LMs) to intelligently select and execute patterns, streamlining your CI/CD processes and other automation tasks. Explore the examples to see how `fabric-agent-action` can simplify and enhance your workflows with advanced AI-driven automation?

## Examples

| Example  | Links |
| ---  | --- |
| Create pull request on changes in `README.md` to run [improve writing pattern](https://github.com/danielmiessler/fabric/blob/main/patterns/improve_writing/system.md) | [Pull request](https://github.com/xvnpw/fabric-agent-action-examples/pull/4), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-readme-pr.yml) |
| Create pull request on changes in `docs/` directory to run improve writing pattern | [Pull request](https://github.com/xvnpw/fabric-agent-action-examples/pull/8), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-docs-pr.yml) |
| Run fabric patterns from issue comment - [single_command agent](https://github.com/xvnpw/fabric-agent-action?tab=readme-ov-file#single_command) | [Issue](https://github.com/xvnpw/fabric-agent-action-examples/issues/5), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-issue-agent-single-command.yml) |
| Run fabric patterns from issue comment - [react agent](https://github.com/xvnpw/fabric-agent-action?tab=readme-ov-file#react) | [Issue](https://github.com/xvnpw/fabric-agent-action-examples/issues/6), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-issue-agent-react.yml) |
| Automatically run fabric [write-pull-request pattern](https://github.com/danielmiessler/fabric/blob/main/patterns/write_pull-request/system.md) on pull request | [Pull request](https://github.com/xvnpw/fabric-agent-action-examples/pull/7), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-pr-diff.yml) |