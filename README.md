# Financial Tracker

## How to run

```sh
npm install
npm run dev
```

## Using this example to create

Run the following command:

### TurboRepo

```sh
npx create-turbo@latest
```

remove unnecessary file

- clear apps folder
- clear packages folder

## go to the apps folder to create frontend and backend

```sh
cd apps
```

### ReactJs (vite)

```sh
npm create vite@latest
or
npm create vite@latest client
```

### NestJs

```sh
npm i -g @nestjs/cli

nest new your-project-name
or
nest new api
```

Remove Nested Git Repository:

```sh
cd api

# check if there is a .git directory
ls -a

# if there is a .git directory, remove it
rm -rf .git
```

after removing the nested .git directory, go back to root file and add the changes:

```sh
cd ..

# add all change
git add .
```
