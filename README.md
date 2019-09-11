<p align="center">
<h3 align="center">Simple NextJS Project.</h3></p>
</p>

## Contents

- [Installation](#installation)
- [Development Workflow](#development-workflow)
- [Deployment](#deployment)
- [Deploy to Netlify](#deploy-to-netlify)

### Installation

Clone repo:

```sh
git clone https://github.com/NaderYasser/BitzPrice.git
cd BitzPrice
```


Install the dependencies:

```sh
yarn install
```

or

```sh
npm install
```

### Development Workflow

Start a live-reload development server:

```sh
yarn dev
```

or

```sh
npm run dev
```

Generate a production build:

```sh
yarn build
```

or

```sh
npm run build
```

### Deploy to Now

```sh
now dev
```

For production, update alias in the now.json ie `"alias": "nextss-yourname.now.sh",`

```sh
now
```


