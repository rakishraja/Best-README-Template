<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->

<br />
<div align="center">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Unknown Ransomware Attacks</h3>

  <p align="center">
    <br />
    <a href="https://github.com/rakishraja/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/rakishraja/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/rakishraja/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/rakishraja/Best-README-Template/issues">Request Feature</a>
  </p>
 
</div>

<!-- TABLE OF CONTENTS -->
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

<!-- ABOUT THE PROJECT -->
## About The Project

This project consists of two applications and utilizes a powerful open-source tool:

### Sangraha 360 (SG360)

SG360, an Android malware detection app, uses machine learning to classify installed apps. It employs Django for efficient backend handling and stores data securely in MongoDB.

### Dṛḍhagā 360 (DG360)

Dṛḍhagā 360 (CG360) deploys federated learning, utilizing CIFAR-10, Kotlin, Malimg, and KronoDroid datasets for robust malware detection. It features an optimized MLP model for efficiency and privacy, with predictions available via a Django server interface.

### Mobile Security Framework (MobSF)

MobSF, an open-source tool, generates static and dynamic data dumps for mobile app security assessments. It enhances app security and device resilience.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This section lists all the major frameworks/libraries/technologies used to bootstrap this project.

### Sangraha 360 (SG360)

- Kotlin
- Firebase
- Amazon Cloud EC2 Instance
- Python

### Dṛḍhagā 360 (DG360)

- Python 3.5
- TensorFlow
- TensorFlow Lite
- Scikit-multiflow
- Flower
- Kotlin
- Amazon Cloud EC2 Instance
- django

### Mobile Security Framework (MobSF)

- Docker
- Python
- Flask
- JADX
- Frida
- Apktool

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

This is a list things you need to use the software.

### Sangraha 360 (SG360)

* Firebase setup
* Android Studio
* Android device/ Emulator (SDK>=21)
* django
* mongodb

### Dṛḍhagā 360 (DG360)

* Android Studio
* Android device/ Emulator (SDK>=21)
* GPU (recommended for training and inference speed)
* Python (latest version recommended; Python 3.5 or newer versions compatible)
* Install PyTorch and TensorFlow (latest stable version, use your OS's package manager, and select CUDA if you have a GPU or CPU if not)
* JDK version 16
* npm (for Django server dependencies)
* scikit-multiflow
* django

### Mobile Security Framework (MobSF)

* Docker
* Python 3.x
* Dependencies listed in the requirements file

### 

### Installation

### Sangraha 360 (SG360)

To get started, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/rakishraja/Malware_detector.git
   
2. Setup a Firebase Instance:

   - Visit the [Firebase Console](https://console.firebase.google.com/).
   - Create a new project for Sangraha 360.
   - Set up Firebase Authentication and Firestore for your project.
   - Obtain your Firebase configuration details.

### Dṛḍhagā 360 (DG360)

To get started, follow these steps:

1. Clone the repository:
   ```sh
    git clone https://github.com/msripooja/kmit-cg360-FL.git

### Mobile Security Framework (MobSF)

To get started, follow these steps:

1. **Install MobSF via pip:**
   
   ```shell
   pip install mobsf
   
**Docker Setup (Optional and Recommended)**

Alternatively, for an even easier setup, you can use MobSF within a Docker container. Simply follow these steps:

1. Pull the MobSF Docker image from Docker Hub:

   ```shell
   docker pull mobsf/mobsf

2. Run the Docker container with MobSF:

   ```shell
   docker run -it -p 8000:8000 mobsf/mobsf

This will provide a pre-configured MobSF environment within a Docker container, making it easy to use.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

### Sangraha 360 (SG360)

Use Sangraha 360 (SG360) to detect malicious applications on Android devices.

### Dṛḍhagā 360 (DG360)

Dṛḍhagā 360 (DG360) is to set up the federated learning techniques on Android and Windows.

### Mobile Security Framework (MobSF)

MobSF is a versatile tool that allows you to generate data dumps of APK files for security assessment.

_Usage videos and screenshots and documentation of the various applications based on the functionality of the apps_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] Devising a set frequency to dump data to the server

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Your Name - [@BajrangKailasa](https://twitter.com/BajrangKailasa) - kailasabajrang6@example.com

Project Link: [https://github.com/msripooja/kmit-cg360-android](https://github.com/msripooja/kmit-cg360-android)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/rakishraja/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/rakishraja/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/rakishraja/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/rakishraja/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/rakishraja/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: www.linkedin.com/in/raja-gandewar-a029a827b
