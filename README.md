<h1><img align="right" src="./sticker.svg" width="30%" /> IntervalTrees</h1>

[![Latest Release](https://img.shields.io/github/release/BioJulia/IntervalTrees.jl.svg?style=flat-square)](https://github.com/BioJulia/IntervalTrees.jl/releases/latest)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](https://github.com/BioJulia/IntervalTrees.jl/blob/master/LICENSE)
[![Stable documentation](https://img.shields.io/badge/docs-stable-blue.svg?style=flat-square)](https://biojulia.github.io/IntervalTrees.jl/stable)
![Lifecycle](https://img.shields.io/badge/lifecycle-stable-green.svg?style=flat-square)
[![Chat on Discord](https://img.shields.io/badge/discord-chat-blue.svg?style=flat-square&logo=discord&colorB=%237289DA)](https://discord.gg/z73YNFz)

## Description

IntervalTrees provides the type: `IntervalTree{K, V}`.
It implements an associative container mapping `(K, K)` pairs to to values of type `V`.
`K` may be any ordered type, but only pairs `(a, b)` where `a ≤ b` can be stored.
In other words they are associative contains that map intervals to values.


## Installation

Install IntervalTrees from the Julia REPL:

```julia
using Pkg
add("IntervalTrees")
# Pkg.add("IntervalTrees") for julia prior to v0.7
```

If you are interested in the cutting edge of the development, please check out
the master branch to try new features before release.


## Testing

IntervalTrees is tested against Julia `0.7` on Linux, OS X, and Windows.

| **PackageEvaluator** | **Latest Build Status** |
|:--------------------:|:-----------------------:|
| [![](http://pkg.julialang.org/badges/IntervalTrees_0.7.svg)](http://pkg.julialang.org/?pkg=IntervalTrees) | [![](https://travis-ci.org/BioJulia/IntervalTrees.jl.svg?branch=master)](https://travis-ci.org/BioJulia/IntervalTrees.jl) [![Build status](https://ci.appveyor.com/api/projects/status/3rwbgr40npp95upe/branch/master?svg=true)](https://ci.appveyor.com/project/BenJWard/intervaltrees-jl/branch/master) [![](https://codecov.io/gh/BioJulia/IntervalTrees.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/BioJulia/IntervalTrees.jl) |


## Contributing

We appreciate contributions from users including reporting bugs, fixing
issues, improving performance and adding new features.

Take a look at the [CONTRIBUTING](CONTRIBUTING.md) file provided with
every BioJulia package package for detailed contributor and maintainer
guidelines.


### Financial contributions

We also welcome financial contributions in full transparency on our
[open collective](https://opencollective.com/biojulia).
Anyone can file an expense. If the expense makes sense for the development
of the community, it will be "merged" in the ledger of our open collective by
the core contributors and the person who filed the expense will be reimbursed.


# Backers & Sponsors

Thank you to all our backers and sponsors!

Love our work and community? [Become a backer](https://opencollective.com/biojulia#backer).

[![backers](https://opencollective.com/biojulia/backers.svg?width=890)](https://opencollective.com/biojulia#backers)

Does your company use BioJulia? Help keep BioJulia feature rich and healthy by
[sponsoring the project](https://opencollective.com/biojulia#sponsor)
Your logo will show up here with a link to your website.

[![](https://opencollective.com/biojulia/sponsor/0/avatar.svg)](https://opencollective.com/biojulia/sponsor/0/website)
[![](https://opencollective.com/biojulia/sponsor/1/avatar.svg)](https://opencollective.com/biojulia/sponsor/1/website)
[![](https://opencollective.com/biojulia/sponsor/2/avatar.svg)](https://opencollective.com/biojulia/sponsor/2/website)
[![](https://opencollective.com/biojulia/sponsor/3/avatar.svg)](https://opencollective.com/biojulia/sponsor/3/website)
[![](https://opencollective.com/biojulia/sponsor/4/avatar.svg)](https://opencollective.com/biojulia/sponsor/4/website)
[![](https://opencollective.com/biojulia/sponsor/5/avatar.svg)](https://opencollective.com/biojulia/sponsor/5/website)
[![](https://opencollective.com/biojulia/sponsor/6/avatar.svg)](https://opencollective.com/biojulia/sponsor/6/website)
[![](https://opencollective.com/biojulia/sponsor/7/avatar.svg)](https://opencollective.com/biojulia/sponsor/7/website)
[![](https://opencollective.com/biojulia/sponsor/8/avatar.svg)](https://opencollective.com/biojulia/sponsor/8/website)
[![](https://opencollective.com/biojulia/sponsor/9/avatar.svg)](https://opencollective.com/biojulia/sponsor/9/website)


## Questions?

If you have a question about contributing or using BioJulia software, come
on over and chat to us on [Discord](https://discord.gg/z73YNFz), or you can try the
[Bio category of the Julia discourse site](https://discourse.julialang.org/c/domain/bio).
