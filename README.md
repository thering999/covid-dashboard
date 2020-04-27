# Covid-19 Dashboard

## Software requirements
- Node.js 10.x
- Angular 9.x
- Bootstrap 4.x
- AdminLTE 3.x

## Installation

```
git clone https://gitlab.com/siteslave/covid-dashboard.git
cd covid-dashboard
npm i
```

## Running

```
npm start
```

## Building

```
npm run build
```

## Docker

```
docker run -p 88:80 --name covid-dashboard -d registry.gitlab.com/siteslave/covid-dashboard
```

## Docker compose

```
version: "3"
services:
  covid-dashboard:
    image: "registry.gitlab.com/siteslave/covid-dashboard"
    container_name: "covid-dashboard"
    ports:
      - 88:80

    restart: always
```


Open `http://localhost:88`

Demo online https://r7app.moph.go.th/covid-dashboard/

## Screen Short

![](ss/ss1.png)

![](ss/ss2.png)
