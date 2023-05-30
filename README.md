
<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>
Google-Auth__server
</h1>
<h3 align="center">📍 Secure Authentication with Google-Auth Server: Powering Access Beyond the Cloud</h3>
<h3 align="center">🚀 Developed with the software and tools below.</h3>
<p align="center">

<img src="https://img.shields.io/badge/Redux-764ABC.svg?style=for-the-badge&logo=Redux&logoColor=white" alt="Redux" />
<img src="https://img.shields.io/badge/React-61DAFB.svg?style=for-the-badge&logo=React&logoColor=black" alt="React" />
<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=for-the-badge&logo=Axios&logoColor=white" alt="Axios" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style=for-the-badge&logo=JSON&logoColor=white" alt="JSON" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=HTML5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style=for-the-badge&logo=Markdown&logoColor=white" alt="Markdown" />
</p>

</div>

---

## 📚 Table of Contents
- [📚 Table of Contents](#-table-of-contents)
- [📍Overview](#-introdcution)
- [🔮 Features](#-features)
- [⚙️ Project Structure](#-project-structure)
- [🧩 Modules](#-modules)
- [🏎💨 Getting Started](#-getting-started)
- [🤝 Contributing](#-contributing)
- [🪪 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

---


## 📍Overview

This Google-Auth__server GitHub project is a powerful tool designed to enable users to log into their Google account securely. Using the latest encryption technology, the project provides authentication and authorization services to users to ensure their data and accounts remain safe. Additionally, users can take advantage of the Youtube API integration which enables them to access and manage their Youtube accounts easily and securely. This project provides users with a secure and convenient way to manage their accounts, and is an invaluable tool for anyone who needs to access their Google account regularly.

---

## 🔮 Feautres

### Distinctive Features

1. **User-Centered Design:** The user-centered design elements and architecture of the Google-Auth__server GitHub project focuses on creating a secure, intuitive, and seamless user experience. Authentication is handled using a custom-built OAuth2 workflow, allowing for secure user authentication with Google. Client-side components are designed to provide users with a clean, minimalistic interface, and APIs are provided for easy integration with other services.

2. **Unique Features:** The Google-Auth__server GitHub project stands out from other projects due to its unique features. These include: 
- A custom-built authentication workflow using OAuth2 to ensure secure user authentication with Google 
- Client-side components designed to provide users with a clean, minimalistic interface 
- APIs for easy integration with other services 
- A configurable authentication server that is lightweight and can be easily deployed 
- A set of models for user-related data that are stored in a MongoDB database 
- A “Channel List” component that handles all channel-related logic, from adding new channels to handling authentication requests 
- A “Header” component that handles all navigation-related logic, from managing user sessions to handling authorization requests 
- An “App” component that serves as the entry point to the application, providing access to the authentication server and the various components 
- An “Actions” and “Reducers” component that handles all user-related logic, from user authentication to data management.

---


<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-github-open.svg" width="80" />

## ⚙️ Project Structure


```bash
repo
├── client
│   ├── README.md
│   ├── package-lock.json
│   ├── package.json
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   └── manifest.json
│   └── src
│       ├── actions
│       │   ├── index.js
│       │   └── types.js
│       ├── components
│       │   ├── App.js
│       │   ├── ChannelList.js
│       │   ├── Header.js
│       │   └── Landing.js
│       ├── index.js
│       ├── reducers
│       │   ├── authReducer.js
│       │   ├── channelsReducer.js
│       │   └── index.js
│       ├── serviceWorker.js
│       └── setupProxy.js
├── config
│   ├── keys.js
│   └── prod.js
├── index.js
├── models
│   └── User.js
├── package-lock.json
├── package.json
├── routes
│   ├── authRoutes.js
│   └── youtubeRoutes.js
└── services
    └── passport.js

11 directories, 27 files
```

---

<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-src-open.svg" width="80" />

## 💻 Modules

<details closed><summary>Actions</summary>

| File     | Module                      |
|:---------|:----------------------------|
| types.js | client/src/actions/types.js |
| index.js | client/src/actions/index.js |

</details>

<details closed><summary>Components</summary>

| File           |  Module                              |
|:---------------|:-------------------------------------|
| ChannelList.js | client/src/components/ChannelList.js |
| Landing.js     | client/src/components/Landing.js     |
| Header.js      | client/src/components/Header.js      |
| App.js         | client/src/components/App.js         |

</details>

<details closed><summary>Config</summary>

| File    | Module         |
|:--------|:---------------|
| keys.js | config/keys.js |
| prod.js | config/prod.js |

</details>

<details closed><summary>Models</summary>

| File    | Module         |
|:--------|:---------------|
| User.js | models/User.js |

</details>

<details closed><summary>Public</summary>

| File        | Module                    |
|:------------|:--------------------------|
| favicon.ico | client/public/favicon.ico |
| index.html  | client/public/index.html  |

</details>

<details closed><summary>Reducers</summary>

| File               | Module                                 |
|:-------------------|:---------------------------------------|
| index.js           | client/src/reducers/index.js           |
| channelsReducer.js | client/src/reducers/channelsReducer.js |
| authReducer.js     | client/src/reducers/authReducer.js     |

</details>

<details closed><summary>Root</summary>

| File     | Module   |
|:---------|:---------|
| index.js | index.js |

</details>

<details closed><summary>Routes</summary>

| File             | Module                  |
|:-----------------|-------------------------|
| authRoutes.js    | routes/authRoutes.js    |
| youtubeRoutes.js | routes/youtubeRoutes.js |

</details>

<details closed><summary>Services</summary>

| File        | Module               |
|:------------|:---------------------|
| passport.js | services/passport.js |

</details>

<details closed><summary>Src</summary>

| File             | Module                      |
|:-----------------|:----------------------------|
| index.js         | client/src/index.js         |
| serviceWorker.js | client/src/serviceWorker.js |

</details>

<hr />

## 🚀 Getting Started

### ✅ Prerequisites

Before you begin, ensure that you have the following prerequisites installed:
> `Make sure you have the latest NodeJS runtime installed`

> `You'll need to have NPM installed (it comes with NodeJS)`

### 💻 Installation

1. Clone the Google-Auth__server repository:
```sh
git clone https://github.com/dzenis-h/Google-Auth__server
```

2. Change to the project directory:
```sh
cd Google-Auth__server
```

3. Install the dependencies:
```sh
npm install
```

### 🤖 Using Google-Auth__server

```sh
node app.js
```

<hr />


## 🛠 Future Development
- [X] [📌  CREATE-A-README-FILE]
- [ ] [📌  ADD-SUMMARY-SECTION]
- [ ] [📌  UPDATE-DEPENDENCIES]


---

## 🤝 Contributing
Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a pull request to the original repository.
Open a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 🪪 License

This project is licensed under the `MIT` license. See the [LICENSE](https://docs.google.com/document/d/11WK7tVoTFRMcWCuGZQCRWxEsDUEJ_6ArtfV-NjWcBCU/edit?usp=sharing) file for additional info.

---

## 🙏 Acknowledgments

This was created by [Dzenis H.](https://www.dzenis.tech)

If you like what you see, please consider giving a ⭐️


---

