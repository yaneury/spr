![logo](docs/git_spr_logo.png)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build](https://github.com/ejoffe/spr/actions/workflows/ci.yml/badge.svg)](https://github.com/ejoffe/spr/actions/workflows/ci.yml)
[![ReportCard](https://goreportcard.com/badge/github.com/ejoffe/spr)](https://goreportcard.com/report/github.com/ejoffe/spr)
[![Doc](https://godoc.org/github.com/ejoffe/spr?status.svg)](https://godoc.org/github.com/ejoffe/spr)
[![Release](https://img.shields.io/github/release/ejoffe/spr.svg)](https://GitHub.com/ejoffe/spr/releases/) 
[![Join the chat at https://gitter.im/ejoffe-spr/community](https://badges.gitter.im/ejoffe-spr/community.svg)](https://gitter.im/ejoffe-spr/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

![terminal cast](docs/git_spr_cast.gif)
# Stacked Pull Requests on GitHub

Easily manage stacks of pull requests on GitHub. 
`git spr` is a client side tool that achieves a simple streamlined stacked diff workflow using github pull requests and branches. `git spr` manages your pull request stacks for you, so you don't have to. 

With `git spr` each commit becomes a pull request, and each branch becomes a stack of pull requests. This allows for multiple commits to be stacked on top of each other in a single branch, avoiding the overhead of starting a new branch for every new change or feature. Small changes and pull requests are easy and fast to achieve. One doesn't have to worry about stacked branches on top of each other and managing complicated pull request stacks. The end result is a more streamlined faster software development cycle.

# Notice
This is a fork of the [SPR](https://github.com/ejoffe/spr) project with support
for Merge Queues reverted. This repo is only needed if your GitHub Enterprise
server doesn't support Merge Queues. Once the upstream [issue](https://github.com/ejoffe/spr/issues/356)
is resolved, this repo won't be needed.

Releases track upstream with the caveat that the merge queue commit is reverted.

# Installation

To install, fetch the release packages for your platform in the [Releases](https://github.com/yaneury/spr/releases) page.
