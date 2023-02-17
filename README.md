# dxw Terraform Code Playbook

Are you looking for the Terraform Code Playbook? Read and search it at
[terraform-code-playbook.dxw.com](https://terraform-code-playbook.dxw.com).

## What is this?

It’s dxw’s Terraform Code Playbook. It's our reference for creating
maintainable Terraform projects and modules.

## Changes

See the
[This Playbook](https://terraform-code-playbook.dxw.com/#this-playbook) section for
information on how to make changes to this documentation.

## Development guide

### Setup

Run the setup command. This installs the dependencies required for running the
project.

```
script/setup
```

To just update dependencies, you can run the bootstrap command (though this
currently does the same as `script/setup` due to the small number of
dependencies required):

```
script/bootstrap
```

### Running the application

To run the server, from the root directory, run:

```
script/server
```

This runs the server on localhost:4000.

### Checking the HTML

To proof the HTML for things like dead links, run:

```
bundle exec jekyll build
bundle exec htmlproofer _site
```

## Licence

The contents of dxw's Terraform Code Playbook is released under a
[Creative Commons Attribution-NonCommercial](https://creativecommons.org/licenses/by-nc/2.0/uk/)
licence. You are free to reuse and adapt this content with credit, for
non-commercial purposes.
