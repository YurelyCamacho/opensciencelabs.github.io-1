---
title: "Collaborating and learning from SciCookie"
slug: scicookie-collaborating-and-learning
date: 2024-02-03
authors: ["Daniela Iglesias Rocabado"]
tags: [open-source, open-science, python, proyects]
categories: [python]
description: |
  The SciCookie template, developed by Open Science Labs, is a Python package based on the Cookieninja A Cookiecutter Fork
  command-line utility. Serving as a versatile boilerplate, it simplifies project creation for both beginners and experienced
  developers, saving significant time. Derived from ongoing research on scientific Python tools and best practices, SciCookie
  aligns with PyOpenSci recommendations, providing a standardized starting point for projects that can be easily customized
  while adhering to industry standards.
thumbnail: "/header.jpeg"
template: "blog-post.html"
---
# SciCookie

The SciCookie template, developed by Open Science Labs, is a project template tool package, that uses Cookieninja as a backend, a Cookiecutter fork. Functioning as a versatile boilerplate, it facilitates project creation for both beginners and experienced developers, streamlining the process and saving considerable time. SciCookie provides an initial project layout with recommended tools, workflows, and structure. Additionally, it incorporates features like automatic documentation generation, automated testing, and project-specific configuration to enhance the development workflow. The template is aligned with PyOpenSci recommendations, derived from ongoing research on tools, libraries, best practices, and workflows in scientific Python. As a result, SciCookie offers authors a standardized starting point for projects that can be easily adjusted to meet specific requirements while maintaining industry standards.


## Benefits of using SciCookie

- **Organized Workflow:** Utilizing the SciCookie template allows for maintaining an organized workflow. By configuring elements such as project design, build system, command-line interface, and documentation engine, the development process is streamlined, ensuring a coherent and organized framework for the project.
- **Enhanced Project Tools:** SciCookie provides the flexibility to choose from various tools that can enhance the project. These tools automate tasks, ensure consistent code formatting, and identify errors and vulnerabilities.
- **DevOps Integration:** Another significant benefit is the seamless integration of the Python project with DevOps tools. These tools automate and optimize the development process, from code status to completion and maintenance.

## How to use SciCookie?

### Quickstart

>**Note:**
Navigate to the folder where you want to create your project.


```bash
$ pip install scicookie
```

Once you have entered your folder, you need to generate a Python package project:

```bash
$ scicookie
```

## SciCookie profiles

SciCookie enables the community to create different profiles within SciCookie's platform tailored to the standards and preferences of each group or working community. Currently, only the OSL profile is available, but it is open to the community to submit pull requests with specific profiles. Each profile offers different configuration options to choose required tools, define titles for specific messages, and also set titles for documentation and help URLs.

```bash
$ scicookie --profile osl
```

### Demo Video

For a better explanation, please watch a demonstrative video of the installation of SciCookie and the creation of a project using the OSL profile.

<iframe width="560" height="315" src="https://www.youtube.com/embed/GozNb4i47Ds" frameborder="0" allowfullscreen></iframe>

