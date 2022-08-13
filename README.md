# How to Build Crypto Tracker using React and Docker


## Technical Stack

- React.JS
- Docker

## How it works?

CoinTracker automatically syncs all crypto into one unified dashboard and helps users see all crypto currency at one place.


## Prerequisite

- Install Docker

## Step1 - Clone the repository

```
 git clone https://github.com/open-source-chandigarh/cryptotracker
```

## Step2 - Change directory to cryptotracker

```
 cd cryptotracker
```

## Step3 - Create docker image

```
docker build -t cryptotracker .
```

## Step4 - Run it on server

```
 docker run -p 3000:3000 cryptotracker
```

<img width="1039" alt="image" src="https://user-images.githubusercontent.com/34368930/183389616-98d53502-a4a4-4e2e-9145-e43823c4c929.png">
