# Chaos experiments for Azure

This project is a collection of [chaos experiments][experiment] that mainly target the [Microsoft Azure][azure] platform.

[experiment]: https://docs.proofdock.io/chaos/guide/#experiment
[azure]: https://azure.microsoft.com/en-us/

## Install

Make sure that you have [installed][proofdock_install] the Proofdock Chaos CLI and [configured][proofdock_configure] the Chaos Engineering Platform and the CLI properly in order to run the experiments in this repository.

[proofdock_install]: https://docs.proofdock.io/chaos/guide/install.html
[proofdock_configure]: https://docs.proofdock.io/chaos/guide/configure.html

## Usage

This repository is a GitHub template repository. It should be an ease to import this repository following the [GitHub template instructions][github_template].

Please explore the code to see existing experiments. Most of the experiments are accompanied by blog posts published at the Proofdock's [Medium page][medium_publication].

[github_template]: https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template
[medium_publication]: https://medium.com/proofdock

## Configuration

You have to configure the [Azure Pipelines][azure_pipeline] and experiments with configuration values and secrets:
* Azure Pipelines make use of variable groups to fetch variable values from. Feel free to adapt to your needs in your project.
* For experiments you have to provide API tokens delivered by the [Proofdock Chaos Engineering Platform][proofdock_cep]

[azure_pipeline]: https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines?view=azure-devops
[proofdock_cep]: https://www.proofdock.io

## Contribute

If you wish to contribute more experiments to this package, you are more than welcome to do so. Please, fork this project, make your changes and submit a PR for review.

The Proofdock chaos projects require all contributors to sign a [Developer Certificate of Origin][dco] on each commit they would like to merge into the master branch of the repository. Please, make sure you can abide by the rules of the DCO before submitting a PR.

[dco]: https://developercertificate.org/
