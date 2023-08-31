<a name="readme-top"></a>

<div align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![NPM][npm-shield]][npm-url]

</div>

<br />
<div align="center">
  <a href="https://github.com/lottojs/ts-config">
    <img src=".github/logo.png" alt="Logo" width="100" height="115">
  </a>

  <h3 align="center">@lottojs/ts-config</h3>

  <p align="center">
    Simple typescript configuration library.
    <br />
    <br />
    <a href="https://github.com/lottojs/ts-config/issues">Report Bug</a>
    ·
    <a href="https://github.com/lottojs/ts-config/issues">Request Feature</a>
  </p>
</div>


## About The Project

Basic typescript configuration package with common settings in order to help as a base pattern to all [LottoJS](https://github.com/lottojs) projects but nothing excludes it to be also used by the community..


<!-- GETTING STARTED -->
## Getting Started

### Installation
   ```sh
    npm i -D @lottojs/ts-config
   ```
### Usage
Create a `tsconfig.json` file at the root of your project.
```json
    {
        "extends": "@lottojs/ts-config/base.json",
        "compilerOptions": {
            "outDir": "dist",
        }
    }
```

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


[contributors-shield]: https://img.shields.io/github/contributors/lottojs/ts-config.svg?style=for-the-badge
[contributors-url]: https://github.com/lottojs/ts-config/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/lottojs/ts-config.svg?style=for-the-badge
[forks-url]: https://github.com/lottojs/ts-config/network/members
[stars-shield]: https://img.shields.io/github/stars/lottojs/ts-config.svg?style=for-the-badge
[stars-url]: https://github.com/lottojs/ts-config/stargazers
[issues-shield]: https://img.shields.io/github/issues/lottojs/ts-config.svg?style=for-the-badge
[issues-url]: https://github.com/lottojs/ts-config/issues
[license-shield]: https://img.shields.io/github/license/lottojs/ts-config.svg?style=for-the-badge
[license-url]: https://github.com/lottojs/ts-config/blob/master/LICENSE.txt
[npm-shield]: https://img.shields.io/npm/v/@lottojs/ts-config?style=for-the-badge&logo=npm&logoColor=FFFFFF&labelColor=555555&color=CB0001
[npm-url]: https://www.npmjs.com/package/@lottojs/ts-config
