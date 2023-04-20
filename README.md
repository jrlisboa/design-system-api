# [Work in Progress] Design System API

This backend project is designed to manage and provide information about items used in a design system, such as color tokens, fonts, sizes, and more. It also handles the registration and retrieval of component details and the tokens used in each of them.

## Stack

The project is built using
- Node.js
- Hapi.js
- MongoDb

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Features

- Register and manage design tokens (colors, fonts, sizes, etc.)
- Register and manage component details
- Retrieve tokens used in specific components
- RESTful API for easy integration with frontend applications

## Requirements

- Node.js v14.x or higher
- npm v6.x or higher
- MongoDB v4.x or higher

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/design-system-backend.git
```

2. Install dependencies:

```bash
npm install
```

1. Running local:

```bash
npm run start:local
```
Server will run using nodemon.

## Usage
The project provides a RESTful API to manage design tokens and components. You can use any API client, such as Postman or Insomnia, to interact with the API.
