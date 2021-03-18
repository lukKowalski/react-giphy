## How it looks:
![image](https://user-images.githubusercontent.com/2960003/111598948-07e00000-87d0-11eb-8de0-07beeb60156a.png)


## Scripts

To start the local Webpack Dev Server (usually on port `8080`):

```bash
yarn start
```

To lint all JavaScript files in the `src` folder:

```bash
yarn lint
```

To build and deploy your app to `gh-pages` branch on the GitHub repo:

```bash
yarn build
```

## Docker

To build docker image:

```bash
docker build -t cats-image .
```

To run built docker image as a container under localhost:8001:

```bash
docker run -dp 8001:8001 cats-image
```

Go to: http://localhost:8001 to search for cat memes with giphy
