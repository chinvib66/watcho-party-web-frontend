# Watcho Party: Web Fronted

> Dishathon 2020: Team hackoverflow

## Installation

Clone the repository to a folder using command prompt/bash shell

```
> git clone https://github.com/chinvib66/watcho-party-web-frontend.git
> cd watcho-party-web-frontend
```

### Install dependencies

```
> npm i
```

Start the app

```
> npm start
```

### Using Docker

Build and tag the docker image

```
> docker build -t watcho-party-fr:dev .
```

Spin up the container once build is done

```
docker run \
    -it \
    --rm \
    -v ${PWD}:/app \
    -v /app/node_modules \
    -p 3001:3000 \
    watcho-party-fr:dev
```

> ### Note: For the sync to work, sync-backend server should be live.

You can edit the sync-backend server endpoint in `.env` file

## Usage

[Youtube Link]()
