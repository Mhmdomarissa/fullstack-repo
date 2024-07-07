I have completed the setup of our project by creating separate repositories for the frontend and backend components.
The frontend-repo contains the frontend code along with (client.py) and a (requirements.txt file), 
while the backend-repo contains the backend code with (server.py) and its own (requirements.txt file).
To centralize shared configuration settings like ServerIPAddress, I created a config.env file in the fullstack-repo. 
Additionally, I added frontend-repo and backend-repo as submodules to the fullstack-repo, allowing us to mirror and synchronize these repositories.
I modified client.py and server.py to load configuration variables from config.env, ensuring consistent settings across both the frontend and backend. 
his setup provides a modular codebase with clear separation of concerns, centralized configuration to reduce errors,
improved collaboration by allowing teams to work independently, and streamlined deployment and testing processes through the central repository (fullstack-repo).
