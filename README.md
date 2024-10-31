<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<div align="justify"> In this project, we explore five distinct approaches for Parameter-Efficient Fine-Tuning of Large Language Models (LLMs): Full Fine-Tuning, Soft Prompting, Adapters, Adapter Hub, and LoRA, applied to the T5-small model for a sentiment analysis task using the IMDB dataset. Here is a brief explanation of each method:
•  Full Fine-Tuning: This approach updates all model parameters during training, enabling maximum model adaptation but requires significant computational resources and storage.
•  Soft Prompting: Instead of altering the model’s core parameters, this method learns a set of “soft prompts” that act as additional input tokens, steering the model towards desired outputs with minimal parameter changes.
•  Adapters: Adapters introduce small, trainable modules into each layer of the model, allowing the main model parameters to remain frozen. This approach is efficient in terms of storage and computation, as only the adapter parameters need updating.
•  Adapter Hub: An extension of the adapter concept, Adapter Hub is a modular framework that enables the sharing and reuse of adapters across tasks. This allows for flexible, plug-and-play fine-tuning of models on multiple tasks with minimal additional training.
•  LoRA (Low-Rank Adaptation): LoRA fine-tunes low-rank matrices within the model, significantly reducing the number of parameters to train. This method is highly parameter-efficient and works well for adapting large language models without substantial resource demands.
 </div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

<div align="justify"> The code for each method is implemented from scratch, with performance comparisons to the popular PEFT library. Each notebook includes in-depth explanations and links for further reading on how each method works. A comprehensive report detailing these approaches is also available in the attached report PDF. </div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Rasoul Zahedifar - rasoul.zahedifar75@gmail.com

GitHub Link: [https://github.com/Rasoul-Zahedifar/Parameter-Efficient-Fine-Tunning-of-LLMs](https://github.com/Rasoul-Zahedifar/Parameter-Efficient-Fine-Tunning-of-LLMs/tree/main)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots.svg?style=for-the-badge
[contributors-url]: https://github.com/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots.svg?style=for-the-badge
[forks-url]: https://github.com/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots/network/members
[stars-shield]: https://img.shields.io/github/stars/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots.svg?style=for-the-badge
[stars-url]: https://github.com/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots/stargazers
[issues-shield]: https://img.shields.io/github/issues/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots.svg?style=for-the-badge
[issues-url]: https://github.com/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots/issues
[license-shield]: https://img.shields.io/github/license/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots.svg?style=for-the-badge
[license-url]: https://github.com/Rasoul-Zahedifar/Lyapunov-Based-Formation-Control-of-Underwater-Robots/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/rasoul-zahedifar
