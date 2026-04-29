🐣 Fluffy Bird
A cosy, aesthetic take on the classic Flappy Bird — soft pastel colours, a gentle floaty bird, and progressively tightening pipes. No frameworks, no dependencies, just a single index.html.

🎮 How to Play

Select the desired Difficulty and start to flap
Fly through the gaps between the pipes without hitting them
Each pipe you clear scores you a point
The gaps start wide and gradually get narrower as your score increases


✨ Features

Cosy pastel colour palette — warm sky, soft greens, golden bird
Animated fluffy bird with wings, eye shine, and beak
Scrolling clouds and a grassy ground
Progressive difficulty — pipes start far apart with big gaps and slowly get closer and tighter
Persistent best score saved to localStorage
Game over screen showing your current score and a PLAY AGAIN button
Fully responsive — scales to fit mobile screens
Buttons to change Difficulty at the start of every Run

🚀 Deploying to AWS Amplify
This project is a single static HTML file — no build step required.

Push index.html (and this README.md) to the root of a GitHub repository
Go to the AWS Amplify Console
Click New app → Host web app
Connect your GitHub account and select your repository and branch
On the build settings screen, clear the build command and set the output directory to /
Click Save and deploy

Amplify will serve index.html directly. No package.json, no config files, nothing else needed.

🗂 Project Structure
/
├── index.html   # The entire game — HTML, CSS, and JS in one file
└── README.md

🛠 Built With
Vanilla HTML, CSS, and JavaScript
Canvas 2D API for rendering
Google Fonts — Baloo 2