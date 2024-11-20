# Fabric Agent Action Examples

This repository provides examples of how to effectively use [fabric-agent-action](https://github.com/xvnpw/fabric-agent-action).

GitHub Action is designed to automate complex workflows through an agent-based approach. Powered by Fabric Patterns and built with lang graph, this action leverages the capabilities of Large Language Models (LMs) to intelligently select and execute patterns, streamlining your CI/CD processes and other automation tasks. Explore the examples to see how `fabric-agent-action` can simplify and enhance your workflows with advanced AI-driven automation.

## Examples

| Example | Links |
| --- | --- |
| Create a pull request on changes in `README.md` to run the [improve_writing pattern](https://github.com/danielmiessler/fabric/blob/main/patterns/improve_writing/system.md) | [Pull request](https://github.com/xvnpw/fabric-agent-action-examples/pull/16), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-readme-pr.yml) |
| Create a pull request on changes in the `docs/` directory to run the `improve_writing` pattern | [Pull request](https://github.com/xvnpw/fabric-agent-action-examples/pull/12), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-docs-pr.yml) |
| Run fabric patterns from issue comments using the [router agent](https://github.com/xvnpw/fabric-agent-action?tab=readme-ov-file#router-agent-router) | [Issue](https://github.com/xvnpw/fabric-agent-action-examples/issues/15), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-issue-agent-router.yml) |
| Run fabric patterns from issue comments using the [react agent](https://github.com/xvnpw/fabric-agent-action?tab=readme-ov-file#react-agent-react) | [Issue](https://github.com/xvnpw/fabric-agent-action-examples/issues/14), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-issue-agent-react.yml) |
| Automatically run the fabric [write_pull_request pattern](https://github.com/danielmiessler/fabric/blob/main/patterns/write_pull-request/system.md) on pull requests | [Pull request](https://github.com/xvnpw/fabric-agent-action-examples/pull/17), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-pr-diff.yml) |
| Run fabric patterns from issue comments using specialized [react issue agent](https://github.com/xvnpw/fabric-agent-action?tab=readme-ov-file#react-issue-agent-react_issue) | [Issue](https://github.com/xvnpw/fabric-agent-action-examples/issues/13), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-issue-agent-react-issue.yml) |
| Run fabric patterns from pull request comments using specialized [react pr agent](https://github.com/xvnpw/fabric-agent-action?tab=readme-ov-file#react-pull-request-agent-react_pr) | [Pull request](https://github.com/xvnpw/fabric-agent-action-examples/pull/17#issuecomment-2488106340), [workflow](https://github.com/xvnpw/fabric-agent-action-examples/blob/main/.github/workflows/fabric-pr-agent-react-pr.yaml) |