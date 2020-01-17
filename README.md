# NextJS and Docker

Enjoy!

### Dev

`npm i && npm run dev`

### Prod

Build your containers for deploys:

MacOS/Linux

`./scripts/prod.sh`

Windows

`./scripts/prod.bat`

Now that your container is built, you can test it locally:

`docker run -p 3000:3000 nextjs-docker`

You can also use `docker-compose up --build`

This will build and run your container locally :smile:

Now deploy :rocket:
