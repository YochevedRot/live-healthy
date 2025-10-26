<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
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
[![License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/yourusername/live-healthy">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Live Healthy</h3>

  <p align="center">
    A personalized nutrition coaching web application.<br/>
    Search recipes by free text, save favorites, and interact with an AI-based personal trainer tailored to your chosen style.
    <br />
    <a href="#about-the-project"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#screenshots">View Screenshots</a>
    &middot;
    <a href="https://github.com/yourusername/live-healthy/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/yourusername/live-healthy/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
        <li><a href="#environment-variables">Environment Variables</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](#screenshots)

**Live Healthy** is a full-stack nutrition coaching system focused on personalization and a clean user experience.

Core capabilities:
* 🔎 **Free-text recipe search** with keywords
* ⭐ **Favorites** to save and manage recipes
* 🧠 **AI Personal Trainer** (GPT) that adapts to a selected coaching style/personality
* 🗂️ Clear modular client/server architecture

Use the `BLANK_README.md` of your choice to start new modules consistently.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

This project uses a straightforward, production-ready stack:

* **Client:** React, TypeScript, Axios (state: Zustand or equivalent)
* **Server:** .NET Core Web API (C#), Entity Framework Core
* **Database:** SQL Server
* **AI:** OpenAI GPT integration (key via environment variables)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Follow the steps below to run the project locally.

### Prerequisites

* Node.js (v18+)
* .NET 8 SDK
* SQL Server (local or remote)

Optional:
```sh
npm install npm@latest -g
