<a id="readme-top"></a>
<!--
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
-->
<br />
<div align="center">
  <a href="https://github.com/Alexandr5656/Educational-Trading-Bot">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Eductional Trading Bot</h3>

  <p align="center">
    I wanted to create a project that hits most aspects of Hedgefund development space. From tooling to trading to FPGA development just to learn as much as possible
    <br />
    <a href="https://github.com/Alexandr5656/Educational-Trading-Bot"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Alexandr5656/Educational-Trading-Bot">View Demo</a>
    &middot;
    <a href="https://github.com/Alexandr5656/Educational-Trading-Bot/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/Alexandr5656/Educational-Trading-Bot/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project
### Built With

* [![C++][cpp-shield]][cpp-url]
* [![Python][python-shield]][python-url]
* [![FPGA][fpga-shield]][fpga-url]
* [![Kubernetes][kubernetes-shield]][kubernetes-url]
* [![Raspberry Pi][raspberrypi-shield]][raspberrypi-url]

## Goals
Over all i want this to be a platform for trading that has many compenets of plug and play usage. By this I mean the platform has to be End2End with ability to develop different compennts at the same time while also testing others independently or even chaining some together. I want this to be End 2 End from data ingestion to testing decisions made by models.
### Models
We need to develop AI models that can deal with time series data. We also need to create a sentiment analysis model. I also think it would be funny to develop a bot that would take in reddit and other social media data for trading decisions.
### Data ingestions
ML and AI models all suffer from the bottle neck of clean data. When data comes it has to be cleaned of anything on needed and normalized for the model to take in. We also need to be able to take in data from a multitude of places that will not follow the same strucutre. For example reddit posts will be obvisouly different from how weather data is structured. Even weather data across different websites as well. Some how all this data has to be structured into some kind of similar format and cleaned as well. This all has to be done as fast as possible as well as the model can only trade based on data its getting and and will only be as fast as its cleaning.
### Dev-Ops
Dev-ops is a pivotal point of any sofwtware development. This will be working on the infrastructure of the whole project. There are many points of the project that need to be worked on. From the docker structure of the project to creating pipelines for automating testing. This section will also be in charge of automating many different pivotal points of the project like flashing the FPGA for trading strategies.
### Testing Platform
Testing has to be done at all stages of the project and be modular enough to be able to test all points of the project. From testing to see if the data cleaning strategies work to testing if the models work based on old but confirmed cleaned data. Maybe eventually also be helpful with debugging models or visualizing data ingested.
### FPGA usage
The FPGA is the coolest part of the project in my opinion. For reference and FPGA is short for a Field Programable Gate Array. This basically means a programmable circuit. In high frequency firms they use FPGA to create instantous trades based on two things. The data thats coming in and what strategies either the trader decides on or the models decide on. From there they program the strats into circuits and use them throughout the day to make decisions in pico seconds.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

* Docker Installation


### Installation

1. 


<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!--
## Usage
-->
<!--
Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.
For more examples, please refer to the [Documentation](https://example.com)
<p align="right">(<a href="#readme-top">back to top</a>)</p>
-->
## Roadmap

- [ ] MVP 1 - Trading Platform
    - [ ] Data Ingestion
    - [ ] Data Cleaning
    - [ ] Model Creation
- [ ] MVP 2 - Performance Optimization
    - [ ] Automating Tools
    - [ ] Performance Testing Tools
    - [ ] Testing Tools
- [ ] MVP 3 - Into The Sky
    - [ ] FPGA Development Onboarding
    - [ ] Cloud Trading
    - [ ] Initial Capital?

See the [open issues](https://github.com/Alexandr5656/Educational-Trading-Bot/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

If you want to join this project put out a pull request adding your name to the contributors below. This is going to start as an educational project with the trading being done with paper trading API's. Once the platform is built and we're in MVP-3 I'll introduce the idea of using real money for the trading. But before that I want it to be clear that this is to be used as a place to learn the aspects of coding at large trading firms. This can help you with job search and future employment as these are all aspects of the jobs I've interviewed for and that interviewers usually looks for. I also don't want you to worry about not knowing a part if your interested in it as we will all teach each other as we go.

### Contributors

- Alex Burbano

### Top contributors:

<a href="https://github.com/Alexandr5656/Educational-Trading-Bot/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Alexandr5656/Educational-Trading-Bot" alt="contrib.rocks image" />
</a>

## License

Distributed under the project_license. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Alex Burbano - [@Linkedin](https://www.linkedin.com/in/alex-burbano/) - Alex@Burbano.me

Project Link: [https://github.com/Alexandr5656/Educational-Trading-Bot](https://github.com/Alexandr5656/Educational-Trading-Bot)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
<!-- MARKDOWN LINKS & IMAGES -->
<!--
[contributors-shield]: https://img.shields.io/github/contributors/Alexandr5656/Educational-Trading-Bot.svg?style=for-the-badge
[contributors-url]: https://github.com/Alexandr5656/Educational-Trading-Bot/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/Alexandr5656/Educational-Trading-Bot.svg?style=for-the-badge
[forks-url]: https://github.com/Alexandr5656/Educational-Trading-Bot/network/members

[stars-shield]: https://img.shields.io/github/stars/Alexandr5656/Educational-Trading-Bot.svg?style=for-the-badge
[stars-url]: https://github.com/Alexandr5656/Educational-Trading-Bot/stargazers

[issues-shield]: https://img.shields.io/github/issues/Alexandr5656/Educational-Trading-Bot.svg?style=for-the-badge
[issues-url]: https://github.com/Alexandr5656/Educational-Trading-Bot/issues

[license-shield]: https://img.shields.io/github/license/Alexandr5656/Educational-Trading-Bot.svg?style=for-the-badge
[license-url]: https://github.com/Alexandr5656/Educational-Trading-Bot/blob/main/LICENSE

[linkedin-shield]: https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin
[linkedin-url]: https://www.linkedin.com/in/alex-burbano/

<!-- Shields.io badges. You can a comprehensive list with many more badges at: https://github.com/inttter/md-badges -->

<!-- TECHNOLOGY SHIELDS -->

[cpp-shield]: https://img.shields.io/badge/C++-%2300599C.svg?logo=c%2B%2B&logoColor=white
[cpp-url]: https://isocpp.org/

[python-shield]: https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff
[python-url]: https://www.python.org/

[fpga-shield]: https://img.shields.io/badge/FPGA-00599C?logo=intel&logoColor=white
[fpga-url]: https://www.intel.com/content/www/us/en/products/details/fpga.html

[kubernetes-shield]: https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white
[kubernetes-url]: https://kubernetes.io/

[raspberrypi-shield]: https://img.shields.io/badge/Raspberry%20Pi-C51A4A?logo=raspberrypi&logoColor=white
[raspberrypi-url]: https://www.raspberrypi.com/

