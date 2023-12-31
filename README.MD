<div align="center" style="background-color: #fff3cd; padding: 10px; border: 1px solid #ffeeba;">
    <p align="center" style="margin: 0; font-weight: bold;">
        <span style="color: #856404;">&#9888;</span> <span>This package is under development! </span>
        <span style="color: #856404;">&#128679;</span>
    </p>
    <p align="center" style="margin: 0;">The release is scheduled for August 16th.</p>
</div>

<p align="center">
  <img src="https://github.com/EddieUFSM/mjest/blob/main/public/logo.png" />
</p>

<p align="center">
 Mjest is a powerful CLI tool that simplifies the structuring and scaffolding of RESTful microservice projects in JavaScript. 
</p>

<p align="center">
  <img alt="Static Badge" src="https://badge.fury.io/js/mongoose-express-sanitizer.svg">
  <img alt="Static Badge" src="https://img.shields.io/badge/licence-MIT-green">
  <a href="https://www.patreon.com/mjest"><img alt="Static Badge" src="https://img.shields.io/badge/patreon-donate-green"></a>
</p>


<h1 align="center">
  Mjest
</h1>

<h2>Descrição</h2>
<p align="justify">
  Mjest is a powerful and intuitive command-line interface (CLI) tool designed to simplify and structure the development of JavaScript-based RESTful API applications. With Mjest, you can easily create a microservice project using popular technologies such as MongoDB, Mongoose, and Express, while benefiting from additional features for unit testing, documentation, and continuous integration and deployment (CICD) to AWS Kubernetes with EKS.
</p>

<h3> Key Features </h3>
<ul>
<li> <p align="justify"> Quick Initialization and Structuring: Mjest enables you to quickly start a new microservice project by automatically setting up the essential folder and file structure needed for RESTful API development. This saves time and effort by providing a solid foundation for your project. </p> </li>
<li> <p align="justify">MongoDB and Mongoose Integration: With Mjest, you can seamlessly integrate MongoDB into your project, utilizing the popular MongoDB object modeling library, Mongoose. Mjest automatically configures the necessary connections, schemas, and models, making it easy to interact with the database.</p> </li>
<li> <p align="justify">Express Framework: Mjest utilizes Express.js, one of the most popular frameworks for building web applications in Node.js. With Express, you can easily create routes, handle middleware, and manage HTTP requests and responses efficiently.</p> </li>
<li> <p align="justify">Unit Testing Foundation: Mjest encourages best development practices, including unit testing to ensure code quality. With built-in support for unit testing, you can write and execute automated tests to validate the correct functioning of your endpoints and business logic.</p> </li>
<li> <p align="justify">Automatic Documentation: Documentation is essential for facilitating the usage and understanding of an API. With Mjest, you can automatically generate clear and concise documentation for your RESTful API, enabling other developers to quickly understand how to consume your endpoints and what parameters to expect.</p> </li>
<li> <p align="justify">Continuous Integration and Deployment (CICD) to AWS Kubernetes with EKS: Mjest simplifies the setup of CICD for Kubernetes, allowing for continuous deployment of your microservice to AWS using Amazon EKS. With just a few commands, you can easily configure automated deployment pipelines, ensuring continuous delivery of your application.</p> </li>
</ul>

<p align="justify">
In summary, Mjest is a comprehensive tool for JavaScript developers who want to quickly and efficiently create and structure RESTful API microservice projects. With built-in support for MongoDB, Mongoose, Express, unit testing, documentation, and CICD to AWS Kubernetes with EKS, Mjest streamlines the entire development lifecycle, allowing you to focus on building powerful and scalable APIs.
</p>

<h2> Features </h2>

- Effortlessly set up well-organized microservice architectures
- Generate project templates with ease
- Configure endpoints and handle middleware seamlessly

<h2> Installation </h2> 

```bash
npm install -g mjest
```

## Usage

```bash
mjest create my-microservice
```
<h2> Documentation </h2>

For detailed usage instructions, API reference, and examples, please refer to the Documentation.

<h2> Contributing </h2>

Contributions are welcome! See the Contributing Guidelines for more details.

<h2> License </h2>

This project is licensed under the MIT License.
 google cloud

```bash
mjest generate base directory to microsservices
```

<h2> base structures </h2>

Directory of Microsservices
```
├──  authentication
├──  authorization
├──  eventEmitter
├──  gateway
└── logger
```

Library endpointDispatcher

```
├── .gitignore
├── .package.json
├── README.md
├── .babelrc
├── .env.example
├── .env
├── .eslintrc
├── src
├── test
└── .github
    ├── cicd.yml
    └── publish.yml
```

Microsservice

```
├── .gitignore
├── .package.json
├── README.md
├── .babelrc
├── .env.example
├── .env
├── .eslintrc
└── src
    ├── index.js
    ├── models.js
└── test
└── .github
    ├── cicd.yaml
```
