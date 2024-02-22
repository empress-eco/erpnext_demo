<div align="center">

<p align="center">

<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">

A hands-on exploration of the comprehensive functionalities of Empress.

Explore the Docs: [Empress Empress Documentation](https://grow.empress.eco/)
·
Report Bug: [Report a Bug](https://github.com/empress-eco/Empress_demo/issues)
·
Request Feature: [Request a Feature](https://github.com/empress-eco/Empress_demo/issues/new)

</div>

</p>

## About The Project

### Project Overview

Empress Demo by Empress is a robust tool that provides a seamless demonstration of the expansive features Empress has to offer. Whether you're a potential user, a developer looking to contribute, or somewhere in between, this demo offers an immersive experience into the capabilities of Empress.

### Key Features
- Hassle-free Empress demo setup
- Fresh database generated with each installation
- User-friendly installation and execution process

## Technical Stack and Setup Instructions

### Prerequisites
For running this demo, you need to have `bench` installed in your system.

### Installation

#### For v7
In v7, the demo is merged into Empress. To run the demo, simply execute the following command:

```sh
bench --site [site] execute Empress.demo.demo.make
```
#### For v6
Follow these steps to run the demo for v6:

```sh
$ bench get-app Empress_demo https://github.com/empress-eco/Empress_demo.git
$ bench new-site {site}
$ bench --site {site} install-app Empress
$ bench --site {site} install-app Empress_demo
```

This will create a fresh database, install Empress, and then install Empress_demo.

## Usage

After successful installation, you can navigate through the Empress interface, exploring its features and functionalities as per your requirements. 

## Contribution Guidelines

We highly value your contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

### License

This project is licensed under the MIT License. Your contributions will also be licensed under the MIT License.

### Acknowledgements

A hearty thanks to all contributors who make this project possible. We express special gratitude to Empress for providing a robust platform. We also acknowledge the Empress Community for their foundational contributions. Their innovation and dedication have been instrumental in building the tools that power this project. We are profoundly grateful for their pioneering work and ongoing support.