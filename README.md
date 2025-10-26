<a id="readme-top"></a>

<br />
<div align="center">
  <a href="https://github.com/yourusername/live-healthy">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Live Healthy</h3>

  <p align="center">
    A personalized nutrition coaching web application.<br/>
    Search recipes by keywords, save favorites, and interact with an AI-based nutrition coach tailored to your chosen style.
    <br /><br />
    <a href="#about-the-project"><strong>Explore the docs »</strong></a>
    &middot;
    <a href="#screenshots">View Screenshots</a>
  </p>
</div>

---

## About The Project

**Live Healthy** is a full-stack nutrition coaching system focused on personalization and a clean user experience.

### Features
- 🥗 Free-text recipe search  
- ⭐ Favorites system  
- 💬 AI-based personal nutrition trainer  
- 🧩 Modern full-stack architecture (React + .NET Core + SQL Server)

---

## Built With

- **Client:** React, TypeScript, Axios  
- **Server:** .NET Core Web API (C#), Entity Framework Core  
- **Database:** SQL Server  
- **AI:** OpenAI GPT API

---

## Getting Started

### Prerequisites
- Node.js v18+
- .NET 8 SDK
- SQL Server (LocalDB / Express / Remote)

---

### 1) Clone the repository
```bash
git clone https://github.com/yourusername/live-healthy.git
cd live-healthy
```

### 2) Install client dependencies and run
```bash
cd Live_healthy-client
npm install
npm run dev
```

### 3) Setup and run the server
```bash
cd ../live_healthy-server
dotnet restore
dotnet build
```
Create a .env file inside the server directory and add your GPT key:
```bash
OPENAI_API_KEY=your_api_key_here
```

### 4) Configure and initialize the database
If migrations already exist (the Migrations folder is present):
```bash
dotnet tool install --global dotnet-ef  # if not already installed
dotnet ef database update
```
If there are no migrations yet:
```bash
dotnet ef migrations add InitialCreate
dotnet ef database update
```

Ensure your appsettings.json contains a valid connection string:
```bash
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\\\mssqllocaldb;Database=LiveHealthyDb;Trusted_Connection=True;MultipleActiveResultSets=true"
  }
}
```

### 5) Run the server
```bash
dotnet run
```


