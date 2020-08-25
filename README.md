<h1 align="center">Go-edlib : Edit distance and string comparison library</h1>

<p align="center">
  <a href="https://travis-ci.org/github/hbollon/go-edlib" target="_blank">
    <img alt="Travis CI" src="https://travis-ci.org/hbollon/go-edlib.svg?branch=master" />
  </a>
  <a href="https://codecov.io/gh/hbollon/go-edlib">
    <img alt="Test coverage" src="https://codecov.io/gh/hbollon/go-edlib/branch/master/graph/badge.svg" />
  </a>
  <a href="https://goreportcard.com/report/github.com/hbollon/go-edlib" target="_blank">
    <img alt="Go Report Card" src="https://goreportcard.com/badge/github.com/hbollon/go-edlib" />
  </a>
  <a href="https://github.com/hbollon/go-edlib/blob/master/LICENSE.md" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://godoc.org/github.com/hbollon/go-edlib" target="_blank">
    <img alt="Documentation link" src="https://godoc.org/github.com/hbollon/go-edlib?status.svg" />
  </a>
</p>

> Golang string comparison and edit distance algorithms library featuring : Levenshtein, LCS, Hamming, Damerau levenshtein (OSA and Adjacent transpositions algorithms) etc...

---

## Table of Contents

- [Requirements](#requirements)
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Documentation](#documentation)
- [Author](#author)
- [Contributing](#-contributing)
- [License](#-license)


---

## Requirements
- [Go](https://golang.org/doc/install) (v1.13+)

## Introduction
Golang open-source library which includes most (and soon all) edit-distance and string comparision algorithms with some extra! 
Designed to be fully compatible with Unicode and ASCII characters!
This library is 100% test covered 😁

## Features
- [Levenshtein](https://en.wikipedia.org/wiki/Levenshtein_distance) ✨
- [LCS](https://en.wikipedia.org/wiki/Levenshtein_distance) (Longest common subsequence) with associated edit distance ✨
- [Hamming](https://en.wikipedia.org/wiki/Hamming_distance) ✨
- [Damerau-Levenshtein](https://en.wikipedia.org/wiki/Damerau%E2%80%93Levenshtein_distance), with following variants :
    - OSA (Optimal string alignment) ✨
    - Adjacent transpositions ✨
    
- ASCII and Unicode compatibility ! 🥳

### Coming soon :
- [Jaro distance](https://en.wikipedia.org/wiki/Jaro%E2%80%93Winkler_distance)
- LCS backtrack and diff functions
- And many more ! 😁


## Installation
Open bash into you project folder and run :

```bash
go get github.com/hbollon/go-edlib
```

And import it into your project.

## Documentation

**You can find all the documentation here :** [Documentation](https://godoc.org/github.com/hbollon/go-edlib) 

## Author

👤 **Hugo Bollon**

* Github: [@hbollon](https://github.com/hbollon)
* LinkedIn: [@Hugo Bollon](https://www.linkedin.com/in/hugo-bollon-68a2381a4/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/hbollon/go-edlib/issues). 

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [Hugo Bollon](https://github.com/hbollon).<br />
This project is [MIT License](https://github.com/hbollon/go-edlib/blob/master/LICENSE.md) licensed.
