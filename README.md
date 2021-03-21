<!-- PROJECT LOGO -->
<p align="center">
  <img src="https://user-images.githubusercontent.com/72297207/111885990-19ecb900-89f1-11eb-9a32-755f8f3cca5b.png" align="center">
  <h3 align="center">Lera Backend</h3>

  <p align="center">
    A MERN Stack App that creates a comprehensive report of an online class after it ends
    <br />
    <br />
    <a href="https://lera-learn.herokuapp.com/">View Demo</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## About The Project

The COVID-19 pandemic has affected educational systems worldwide, leading to the near-total closure of schools, universities and colleges. Most governments decided to temporarily close educational institutions in an attempt to curtail the spread of COVID-19. In response to government restrictions most educational institutions have moved to online platforms such as ms teams, zoom and google meet. As students studying in this method of online education we can vouch for how monotonus it is. To overcome this, we intend to create a video-confrencing solution with the help of the dyte platform. This solution, will integrate a set of analytical tools which are aimed to help the teacher understand which parts of their classes were understood well by the students and which parts weren't. This tool will use some image recognition, participation checking algorithms based on unmutes, and random alerts to check if students are attentive to acheive this. The data, will be presented to the teacher in their teacher dashboard in the form of a time vs participation graph. The students will also be provided with a similar graph to scrub through the recordings and find the most important parts of the class faster.

### Tech Stack

<img src="https://github.com/alokme123/BluePizza/raw/dyteToBackend/docs/Screenshot%202021-03-21%20at%2010.57.46%20PM.png" width="50%" alt="Tech Stack">

### Frontend
<p align="center">
<img src="https://github.com/alokme123/BluePizza/raw/dyteToBackend/docs/Screenshot%202021-03-21%20at%2011.02.06%20PM.png" width="90%" alt="Frontend"></p>

* Checkout Figma Designs at [Figma](https://www.figma.com/file/5MwzaInpTlzv4zTffyOQwa/BluePizza?node-id=0%3A1)
* [Frontend Repo](https://github.com/Akshaya-vc/Devspace)

<!-- GETTING STARTED -->
## Getting Started

Please make sure you have an organization ID and API Key for your application. These can be obtained from the [developer portal](https://dev.dyte.in) as it includes dyte SDK as well as a MongoDB URL.

### Installation
 
1. Clone the repo
```sh
git clone https://github.com/alokme123/bluepizza/tree/dyteToBackend/
```
2. Install NPM packages
```sh
npm install
```
3. Create an `.env` file with your credentials. Use `.env.example` as a template.
```sh
cp .env.example .env
nano .env
```
4. Run the application
```sh
npm start
```

<!-- LICENSE -->
## License

Distributed under the MIT License. See [`LICENSE`](./LICENSE) for more information.
