# FantasticLogo

<!-- badges: start -->
[![Project Status: Inactive - The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
[![License: GPLv3](https://img.shields.io/badge/license-GPLv3-bd0000.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Contributor Covenant 3.0 Code of Conduct Badge](https://img.shields.io/badge/Contributor%20Covenant-3.0-4baaaa.svg)](https://www.contributor-covenant.org/version/3/0/code_of_conduct/)
<!-- badges: end -->

## Overview

`FantasticLogo` is a [NetLogo](https://www.netlogo.org) model for simulating the complex [predator-prey dynamics](https://en.wikipedia.org/wiki/Lotka%E2%80%93Volterra_equations) of bleurghs and oopalamcas, two species native to planet Magy's northern hemisphere. It provides a platform for xenobiology research, allowing users to explore how alien species interact, compete, and adapt within an unfamiliar ecosystem.

> If you find this project useful, please consider giving it a star! [![GitHub repo stars](https://img.shields.io/github/stars/danielvartan/fantasticlogo)](https://github.com/danielvartan/fantasticlogo/)

![FantasticLogo Interface](images/interface.png)

## How It Works

The model operates on a grid of patches, each representing a patch of soil where bleurghs grow and oopalamcas roam.

Oopalamcas are small, purple creatures with voracious appetites and a distinctive croak. Bleurghs are large, carnivorous plants that move slowly and capture prey with their funnel-shaped mouths. In the model, oopalamcas are the prey and bleurghs are the predators.

As the simulation runs, bleurghs grow on patches and, upon reaching maturity, can reproduce by dispersing seeds to random locations. Bleurghs prey on oopalamcas, regulating their population.

<table align="center">
  <tr align="center" valign="middle">
    <td>
      <p><strong>Oopalamca</strong></p>
    </td>
    <td>
      <p><strong>Infant and Adult Bleurgh</strong></p>
    </td>
    <td>
      <p><strong>Plasticoco</strong></p>
    </td>
  </tr>
  <tr align="center" valign="middle">
    <td>
      <img src="images/oopalamca.svg" width="150" />
    </td>
    <td>
      <img src="images/infant-bleurgh.svg" width="150" /> &nbsp;→&nbsp;
      <img src="images/bleurgh.svg" width="150" />
    </td>
    <td>
      <img src="images/plasticoco.svg" width="150" />
    </td>
  </tr>
</table>

## How to Use It

### Setup

To get started, ensure you have [NetLogo](https://www.netlogo.org) installed. This model was developed using NetLogo 7.0.3, so it is recommended to use this version or later.

### Downloading the Model

You can download the latest release of the model from its [GitHub
Releases page](https://github.com/danielvartan/fantasticlogo/releases/latest).
For the development version, you can clone or download its [GitHub
repository](https://github.com/danielvartan/fantasticlogo/) directly.

### Running the Model

Once everything is set, open the `fantasticlogo.nlogox` file located in the
`nlogox` folder to start exploring!

Refer to the `Info` tab in the model for additional details.

## Jokes Aside...

<a href="https://www.imdb.com/title/tt0070544/">
  <img src="images/la-planete-sauvage-cover-reduced.png" align="right" width="200" />
</a>

`FantasticLogo` takes inspiration from René Laloux's 1973 masterpiece, [La Planète Sauvage](https://www.imdb.com/title/tt0070544/). The design mirrors the film's hypnotic atmosphere, where the towering, blue-skinned Draags dominate a world of alien flora and fauna. In this world, humans, known as Oms, are treated as mere pets.

The model's dynamics are grounded in the classic [Lotka-Volterra equations](https://danielvartan.github.io/lotka-volterra/), originally formulated by Alfred J. Lotka ([1925](http://archive.org/details/elementsofphysic017171mbp)) and Vito Volterra ([1926](https://www.nature.com/articles/118558a0)), to describe predator-prey interactions. The code builds on Wilensky's ([1997](http://ccl.northwestern.edu/netlogo/models/WolfSheepPredation)) Wolf Sheep Predation model.

## How to Cite

If you use this model, please cite it to acknowledge the effort invested in its development and maintenance.

To cite `FantasticLogo` please use the following format:

Vartanian, D. *FantasticLogo: Predator-prey dynamics on planet Magy with NetLogo* [Computer software]. [https://github.com/danielvartan/fantasticlogo](https://github.com/danielvartan/fantasticlogo)

A BibLaTeX entry for LaTeX users is:

```latex
@software{vartanian,
  title = {FantasticLogo: Predator-prey dynamics on planet Magy with NetLogo},
  author = {Daniel Vartanian},
  url = {https://github.com/danielvartan/fantasticlogo},
  note = {Computer software}
}
```

## How to Contribute

[![Contributor Covenant 3.0 Code of Conduct Badge](https://img.shields.io/badge/Contributor%20Covenant-3.0-4baaaa.svg)](https://www.contributor-covenant.org/version/3/0/code_of_conduct/)

Contributions are always welcome! Whether you want to report bugs, suggest new features, or help improve the code or documentation, your input makes a difference.

Before opening a new issue, please check the [issues tab](https://github.com/danielvartan/fantasticlogo/issues) to see if your topic has already been reported.

## License

[![](https://img.shields.io/badge/license-GPLv3-bd0000.svg)](https://www.gnu.org/licenses/gpl-3.0)

``` text
Copyright (C) 2025 Daniel Vartanian

FantasticLogo is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program. If not, see <https://www.gnu.org/licenses/>.
```
