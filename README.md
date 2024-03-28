# Node Proxy Server

This Node proxy server is built on top of Node.js, Axios, and Express, providing an easy setup for proxying requests. It can be hosted on Vercel or tested locally.

## Setup

1. Download `node-proxy.zip` from the [Releases](https://github.com/pauwol/node-proxy/releases) tab and extract it.
2. Run `npm install` to install all dependencies.
3. Run `node .` to test locally.

## Deploy

### First Method (Vercel Integration)

1. Create a free Vercel account and connect it with GitHub.
2. Create a GitHub repository with the content of the `node-proxy.zip`.
3. Go to Vercel and create a new project, selecting your new GitHub project.
   
### Second Method (Vercel CLI)

1. Create a free Vercel account.
2. Install Vercel CLI on your PC locally: `npm i -g vercel`.
3. Run `vercel` in your project directory locally.
4. Follow the steps of the command-line interface to deploy.

## Usage

Now you can use the proxy server to forward requests. To utilize it:

- Grab the URL or IP of your Vercel project.
- Add `?url=https://google.com` to the end of the URL.
- Example: `https://<your_domain>?url=https://<your_query>`
- HTTP also works.
  
Have fun with your new proxy REST API!
