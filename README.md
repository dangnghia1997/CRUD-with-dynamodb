# GUIDE

## Install

```bash
npm install
```

## Create Table

```bash
node -e 'require("./app.js").createTable()'
```

## Add Movie

```bash
node -e 'require("./app.js").addMovie("2 Fast 2 Furious", "36")'
node -e 'require("./app.js").addMovie("The Fast and the Furious: Tokyo Drift", "38")'
node -e 'require("./app.js").addMovie("Fast & Furious", "29")'
node -e 'require("./app.js").addMovie("Fast Five", "77")'
node -e 'require("./app.js").addMovie("Fast & Furious 6", "70")'
node -e 'require("./app.js").addMovie("Furious 7", "81")'
node -e 'require("./app.js").addMovie("The Fate of the Furious", "67")'
node -e 'require("./app.js").addMovie("Fast & Furious Presents: Hobbs & Shaw", "67")'
```

## Get All Movies

```bash
node -e 'require("./app.js").getAllMovies()'
```


## Get specific Movie

```bash
node -e 'require("./app.js").getMovie("The Fast and the Furious: Tokyo Drift")'
```

## Update Movie Score

```bash
node -e 'require("./app.js").updateMovieScore("The Fast and the Furious: Tokyo Drift", "40")'
```

## Delete Movie

```bash
node -e 'require("./app.js").deleteMovie("The Fast and the Furious: Tokyo Drift")'
```





