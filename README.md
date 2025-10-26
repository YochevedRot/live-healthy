// create-files.js
const fs = require("fs");

// README content
const readme = `
<!-- Improved compatibility of back to top link -->
<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
  <a href="https://github.com/yourusername/live-healthy">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Live Healthy</h3>

  <p align="center">
    A personalized nutrition coaching web application.<br/>
    Search recipes by keywords, save favorites, and interact with an AI-based nutrition coach tailored to your chosen personality style.
    <br />
    <a href="#about-the-project"><strong>Explore the docs »</strong></a>
    <br /><br />
    <a href="#screenshots">View Screenshots</a>
    &middot;
    <a href="https://github.com/yourusername/live-healthy/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/yourusername/live-healthy/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

---

## About The Project

**Live Healthy** is a full-stack nutrition coaching system built for personalization and user engagement.

**Features**
- 🔍 Free-text recipe search
- ⭐ Favorites management
- 🧠 AI-based personal nutrition trainer
- 🧩 Clean modular architecture (React + .NET Core + SQL)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Built With

* **Client:** React, TypeScript, Axios
* **Server:** .NET Core Web API, Entity Framework Core
* **Database:** SQL Server
* **AI Integration:** OpenAI GPT API

---

## Getting Started

### Prerequisites

* Node.js v18+
* .NET 8 SDK
* SQL Server

### Installation

1. Clone the repo  
   \`git clone https://github.com/yourusername/live-healthy.git\`

2. Install dependencies (Client)  
   \`cd client && npm install && npm run dev\`

3. Run the Server  
   \`cd ../server && dotnet restore && dotnet run\`

4. Add environment variables (.env):
   \`\`\`
   OPENAI_API_KEY=your_api_key_here
   \`\`\`

---

## Screenshots

![Login](images/login.jpg)
![Calorie Search](images/calorie-search.jpg)
![Recipes](images/recipes.jpg)

---

## License

Distributed under a **Private License**.  
Copying, reproduction, or reuse of this code without explicit permission is strictly prohibited.  
See \`LICENSE\` for details.

---

## Contact

Project Repository: [Live Healthy](https://github.com/yourusername/live-healthy)

---

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/yourusername/live-healthy.svg?style=for-the-badge
[contributors-url]: https://github.com/yourusername/live-healthy/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/yourusername/live-healthy.svg?style=for-the-badge
[forks-url]: https://github.com/yourusername/live-healthy/network/members
[stars-shield]: https://img.shields.io/github/stars/yourusername/live-healthy.svg?style=for-the-badge
[stars-url]: https://github.com/yourusername/live-healthy/stargazers
[issues-shield]: https://img.shields.io/github/issues/yourusername/live-healthy.svg?style=for-the-badge
[issues-url]: https://github.com/yourusername/live-healthy/issues
[license-shield]: https://img.shields.io/badge/license-Private-red.svg?style=for-the-badge
[license-url]: LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/yourprofile
`;

// LICENSE content
const license = `
Copyright © 2025 Live Healthy.

All rights reserved.

This project is for personal portfolio and demonstration purposes only.
Unauthorized copying, distribution, modification, or use of any part of this codebase,
in whole or in part, without explicit written permission from the author is strictly prohibited.
`;

fs.writeFileSync("README.md", readme.trim());
fs.writeFileSync("LICENSE", license.trim());
console.log("✅ README.md and LICENSE created successfully!");
