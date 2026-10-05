# Jelly Belly Wiki Project

### By Moses Atia Poston

## Table of Contents

1. [Project Description](#project-description)
2. [Live version](#live)
3. [Project Overview](#project-overview)
4. [Important Note for Running the Application](#important-note-for-running-the-application)
5. [Technologies Used](#technologies-used)
6. [Explore the Project](#explore-the-project)
7. [License](#license)
8. [Contact](#contact)

## [Project Description](#project-description)

The Jelly Belly Wiki Project is an integrated solution comprising a data collection subsystem, a backend API, and a frontend client. This project showcases a comprehensive approach to full-stack web development, with a focus on the Jelly Belly candy brand. The data collection subsystem employs Python scripts for web scraping, the backend API is developed with C# .NET EF Core and MySQL, and the frontend client is built using React.

## [Live versions](#live)

- [Jelly Belly Wiki - UI](https://jelly-belly-wiki.netlify.app/)
- [Jelly Belly Wiki - API](https://jellybellywikiapi.onrender.com/)

* The UI deployed on Netlify.com
* The API deployed on Render.com
* The database deployed on TiDB.com

## [Project Overview](#project-overview)

This project is structured into three main components, each residing in its own submodule within this repository:

1. **Jelly Belly Wiki API Data Collection**: [Repository](https://github.com/switchcasestudio/Jelly-Belly-Wiki-API-Data-Collection): this repository dedicated to scripts and supporting files for data collection, primarily using Python for web scraping from the official Jelly Belly website.

2. **Jelly-Belly-Wiki-API**: [Repository](https://github.com/switchcasestudio/Jelly-Belly-Wiki-API): This repository contains the API implementation and the seeded data from the scraping process. The API is built using C# and EF Core .Net with MySql migrations.

3. **Jelly-Belly-Wiki-Client**: [Repository](https://github.com/switchcasestudio/Jelly_Belly_Wiki_Client): The client-side component focusing on user interface and interaction. It includes all frontend development, offering a visually appealing and demonstrates the API's application and functional user experience.

**Note**
Each submodule is equipped with its own README file, containing detailed instructions, documentation, and specific notes relevant to that part of the project.

## [Important Note for Running the Application](#important-note-for-running-the-application)

In order to fully experience the Jelly Belly Wiki application, it is essential to follow these steps:

1. **API and Database Setup**:

   - First, download and install the API from the `/API` submodule. This step is crucial as the API serves as the backend for the application and interacts with the database.
   - Ensure that the database is properly set up and connected as per the instructions in the API repository.

2. **Client UI Installation**:

   - After setting up the API and database, proceed to download and install the client UI from the `/Client` submodule. The client UI is the frontend of the application and requires the API to be operational for the full functionality.

3. **Data Collection Scripts**:
   - The data collection scripts located in the `/Data-Collection` submodule have already been executed to scrape and seed the data into the API's database. Therefore, it is not necessary to run these scripts for the application to work.
   - These scripts are included in the repository to provide insight into the data collection and preparation process, which is a fundamental aspect of this project.

By following these instructions, you can ensure a smooth setup and enjoy the complete functionality of the Jelly Belly Wiki application.

## [Technologies Used](#technologies-used)

Front-End:

- HTML
- CSS
- JavaScript
- React
- Jest

Back-End:

- C#
- Python
- Selenium WebDriver
- BeautifulSoup
- ASP.NET Core
- Entity Framework Core
- Swagger
- REST API

Database:

- MySQL
- LINQ

AI:

- ChatGPT 4

Deployment:

- TiDB.com
- Render.com
- Netlify.com

## [Explore the Project](#explore-the-project)

I encourage exploring each submodule for a deeper understanding of the individual components and their roles within the project. The submodules are structured to provide a clear and efficient overview of the project's multiple facets, from data collection to user interaction.

Please refer to the README files in each submodule for detailed directions, instructions, and additional notes pertinent to each specific segment of the project.

## [License](#license)

[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) 2023 Moshe Atia Poston.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### [contact](#contact)

If you detect any bug in the program, please reach out to me at [moshikoatia@gmail.com](mailto:moshikoatia@gmail.com).
