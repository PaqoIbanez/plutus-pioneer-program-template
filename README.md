# A Plutus template for "Iteration #2 - Plutus Pioneer Program"

This is a [Plutus](https://github.com/input-output-hk/plutus) template configured to try and run a Plutus Playground Server and it is ready to work with the lectures of the second iteration of Plutus Pioneer Program with a nix based development environment on [Gitpod](https://www.gitpod.io/).

## First steps to get ready
- Click or navigate in a browser to this address [gitpod.io/#https://github.com/PaqoIbanez/plutus-pioneer-program-template](https://gitpod.io/#https://github.com/PaqoIbanez/plutus-pioneer-program-template). (You need to signup on Gitpod with your GitHub, GitLab or Bitbucket account), once you signed up, it will create you a workspace with this template.
- Now you only need to clone the next github repositories:
    - `git clone https://github.com/input-output-hk/plutus.git`
    - `git clone https://github.com/input-output-hk/plutus-pioneer-program.git`

## Run the Plutus Playground Server

Go to plutus/plutus-playground-server directory and run a nix-shell (It might take a while). Once nix-shell is ready, in the same directory type plutus-playground-server.
- `cd plutus`
- `nix-shell` (10 minutes around the first time)
- `cd plutus-playground-client` 
- `plutus-playground-server` (2 minutes around)

Open another terminal (plutus/plutus-playground-server), and in the same directory run npm start (It will take a while the first time, so be patient).
- `cd plutus` 
- `nix-shell` (30 seconds around)
- `cd plutus-playground-client`
- `npm start` (5 minutes around)

## Gitpod Local Companion Installation

We will need to install [Gitpod Local Companion](https://www.gitpod.io/blog/local-app) if we want to open the Plutus Playground in our localhost.

In a terminal run the following:

#### Mac
- `curl -OL https://gitpod.io/static/bin/gitpod-local-companion-darwin`
- `chmod +x ./gitpod-local-companion-*`

#### Linux
- `curl -OL https://gitpod.io/static/bin/gitpod-local-companion-linux`
- `chmod +x ./gitpod-local-companion-*`

#### Windows
- curl -OL https://gitpod.io/static/bin/gitpod-local-companion-windows.exe

## Running Gitpod Local Companion

- `./gitpod-local-companion-[darwin|linux|windows]`
- On windows you can execute gitpod-local-companion-windows.exe

At this point you will be able to open in your browse https://localhost:8009/
