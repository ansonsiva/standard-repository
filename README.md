<p align="center">
  <img src="/logo.png" height="180" />
</p>
<p align="center">
  Open source Git repository template
</p>
<p align="center">
  <a href="https://github.com/misitebao/standard-repository/blob/main/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/misitebao/standard-repository?style=flat-square"></a>
  <a href="https://github.com/misitebao/standard-repository"><img alt="GitHub" src="https://img.shields.io/badge/Readme--Style-standard--repository-brightgreen?style=flat-square"></a>
  <a href="https://github.com/misitebao/standard-repository"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/misitebao/standard-repository?style=flat-square"></a>
  <a href="https://github.com/misitebao"><img alt="GitHub Repo stars" src="https://img.shields.io/badge/author-misitebao-brightgreen?style=flat-square"></a>
</p>

<span id="nav-1"></span>

## Internationalization

[English](README.md) | [简体中文](README.zh-Hans.md)

<span id="nav-2"></span>

## Table of Contents

<details>
  <summary>Click me to Open/Close the directory listing</summary>

- [Internationalization](#nav-1)
- [Table of Contents](#nav-2)
- [Introductions](#nav-3)
  - [Official Website](#nav-3-1)
  - [Background](#nav-3-2)
- [Graphic Demo](#nav-4)
- [Features](#nav-5)
- [Architecture](#nav-6)
- [Getting Started](#nav-7)
- [Maintainer](#nav-8)
- [Contributors](#nav-9)
- [Community Exchange](#nav-10)
- [Part Of Users](#nav-11)
- [Release History](CHANGE.md)
- [Donators](#nav-12)
- [Sponsors](#nav-13)
- [Special Thanks](#nav-14)
- [License](#nav-15)

</details>

<span id="nav-3"></span>

## Introductions

This project is a Github sample warehouse template, the main content is the sample template of README file.

<span id="nav-3-1"></span>

### Official Website

[Recommend a standard repository layout!](https://blog.misitebao.com/posts/%E7%BC%96%E7%A8%8B%E6%8A%80%E6%9C%AF/%E5%A6%82%E4%BD%95%E5%86%99%E5%A5%BD%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E7%9A%84readme-%E8%87%AA%E7%94%A8git%E4%BB%93%E5%BA%93%E6%A8%A1%E6%9D%BF%E5%88%86%E4%BA%AB/)

<span id="nav-3-2"></span>

### Background

When searching for the required tools and libraries in the open source community, I found that there are many excellent code libraries, but there is no good README file or tutorial, which causes users to spend extra time to learn how to use it, so this project provides A standard code base template, hoping to help others.

<span id="nav-4"></span>

## Graphic Demo

[![Click Gif to view the full demo](https://cdn.jsdelivr.net/gh/misitebao/CDN@main/md/template-git-repository-mini.gif)](https://www.youtube.com/embed/bOE3eJ-1eas)

<span id="nav-5"></span>

## Features

- The project logo and corresponding data are displayed in the center
- Provide multi-language functions and sample templates
- README must-have instructions
- Built-in directory navigation function to solve the problem that some Markdown parsing engines cannot parse navigation correctly

<span id="nav-6"></span>

## Architecture

```
|—— .gitee                          Gitee Configuration File
| |—— ISSUE_TEMPLATE.md             Gitee Issue Template
| |—— PULL_REQUEST_TEMPLATE.md      Gitee PR Template
|—— .github                         Github Configuration File
| |—— ISSUE_TEMPLATE                Github Issue Template
| | |—— issue-template-bug.md       Github Issue Bug Template
| | |—— issue-template-feature.md   Github Issue Feature Template
| |—— workflows                     Github Workflows
| | |—— deploy-for-hugo.yml         Github Workflows Hugo Example
| | |—— deploy-for-nodejs.yml       Github Workflows NodeJS Example
| |—— pull-request-template.md      Github PR Template
|—— website                         Project website
|—— CHANGELOG.md                    Release Log
|—— LICENSE                         LICENSE
|—— README.md                       English README
|—— README.zh-Hans.md               Other Language README
|—— README.tmpl.md                  README Template

```

<span id="nav-7"></span>

## Getting Started

[Click me](/copy-template/README.tmpl.md) to view the template file, and then click Edit to copy the template content.

If your README conforms to the standard-repository, you can add a badge to link back to this specification to help others adopt this readme.

[![Readme file conforming to standard-repository](https://img.shields.io/badge/Readme--Style-standard--repository-brightgreen?style=flat-square)](https://github.com/misitebao/standard-repository)

To add in markdown format, please use the following code:

```markdown
[![Readme file conforming to standard-repository](https://img.shields.io/badge/Readme--Style-standard--repository-brightgreen?style=flat-square)](https://github.com/misitebao/standard-repository)
```

<span id="nav-8"></span>

## Maintainer

Thanks to the maintainers of these projects:

<a href="https://github.com/misitebao"><img src="https://github.com/misitebao.png" width="40" height="40" alt="misitebao" title="misitebao"/></a>

<details>
  <summary>Click me to Open/Close the contributors listing</summary>

- [Misitebao](https://github.com/misitebao) - Project author, full stack engineer.

</details>

<span id="nav-9"></span>

## Contributors

Thank you to all the contributors who participated in the development of standard-repository. [Contributors](https://github.com/misitebao/standard-repository/graphs/contributors)

<span id="nav-10"></span>

## Community Exchange

<span id="nav-11"></span>

## Part Of Users

<span id="nav-12"></span>

## Donators

<span id="nav-13"></span>

## Sponsors

<span id="nav-14"></span>

## Special Thanks

<span id="nav-15"></span>

## License

[License MIT](LICENSE)
