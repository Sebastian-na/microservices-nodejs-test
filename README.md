# Node js technical test

In this main repository you find two submodules,
one for the A Microservice (getting current weather of given city),
and the B Microservice (getting the forecast five days ahead of given city)

## Installation

Clone the repository with the code inside each submodule,
for this run the following command in your terminal

```bash
  git clone --recurse-submodules https://github.com/Sebastian-na/microservices-nodejs-test.git
```

Then, you will need to install dependencies inside each submodule.
Inside each submodule directory run:
```bash
  npm install
```

You will also need to configure .env files inside each submodule. There are .env.example
files in each repository so you can create your own.

Particularly, there is an API_KEY env variable that needs to be configured.
This should be your API_KEY for [open weather map api](https://openweathermap.org/).

Note that MICROSERVICE_A_URL should be set to whatever URL Microservice A is running.
Same thing applies for MICROSERVICE_B_URL. 

Finally to run each microservice just run
```bash
  npm run dev
```
in each microservice directory.
