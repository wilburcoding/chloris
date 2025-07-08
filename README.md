# Chloris
An ai-powered management application for florists. The desktop application (this repository) is the actual management application and the demo florist site (wilburcoding/chlorissite) is a demo site that uses a server to connect to the desktop application. 

## How to install
  - Download this repository
  - Then, inside this repository
    - Use `npm install` to install dependencies
    - Run `npm start` to start the application
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
