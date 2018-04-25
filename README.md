## Update

Grab latest projects from the [google sheet](https://docs.google.com/spreadsheets/d/1Fdsz9s0WQlyG72UtCLiSa8_LjtbRI7G8yRBetGhj_vo/edit)

```sh
tasks/update.sh
```

## View changes

Run the project locally with gulp, `open http://localhost:3000`: 

```sh
gulp
```

## Push to src 

Make sure to push all changes to src branch before running the deploy!!!

```sh
git add .
git push origin src
```


## Deploy to master

Make sure .tmp folder is empty

```sh
tasks/build.sh
```
