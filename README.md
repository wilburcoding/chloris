# Chloris
An ai-powered management application for florists

## How to install
  - Download this repository, the `chlorisserver` folder, as well as the `chlorissite`
    - This is the main desktop application, the server handles backend requests, and the site is a demo florist website with the application
  - First, inside the server folder
    - Install `scikit-learn` and `flask` with `pip`
    - Run `npm install` to install dependencies
    - Start the machine learning model API with `python ml.py`
    - Start the AI (using Gemini API) using `node index.js`
  - Then, inside this repository
    - Use `npm install` to install dependencies
    - Run `npm start` to start the application
  - For the demo website
    - Use the Visual Studio Code extension `Live Preview` to locally host the static site
  
> It's a lot but the project has quite a lot with it :)

## Features
  - The application itself includes an interactive interface with many tabs including tons of information 
    - Note: The client contact page is a realtime communication system with the website, you can try it out between the application and the demo site!
    - Note: The sidebar for the `Care Assistant` page allows you to ask the AI questions regarding the types of flowers :)
  - The server uses a simple sinusoidal regressiona model as well as Gemini API
  - The site has a couple features
    - AI assistant (bottom right) for questions regarding flowers
    - Ordering page (appears on the dashboard of the application!)
    - Communicate with florist (also appears on the dashboard of the application!)
