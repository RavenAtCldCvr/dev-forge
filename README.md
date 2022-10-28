# Dev-Forge
> Automatically scaffolds a collection of technology specific best practices

Ever wanted to adopt or share an opinated set of best practices when working on a new project?
Dev-Forge strives to consolidate such practices and offer them to your project with a few terminal commands.

## Usage
Currently supports the following technologies
* .NET

## Getting started
1. Create a new github repository, selecting RavenAtCldCvr/dev-forge as a template.
2. Clone the newly created repository
3. Run devf script to scaffolds a supported technology.

```shell
devf.sh dotnet
```

The script attempts to scaffolds .NET best practices to the current directory in the following steps:
1. Copy best practices from the general and dotnet folder to the current directory.
1. Files with the same name will be overwritten implictly.
1. Remove unused files and folders provisioned by the template

## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome.