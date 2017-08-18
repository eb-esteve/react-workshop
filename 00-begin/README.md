# Step 0 - Begin

The goal of this step is just to get everything set up with a running (blank) app.

## Setup

Assuming you have a version of [node](https://nodejs.org/en/) installed, [install `nvm`](https://github.com/creationix/nvm#install-script) and then close & reopen your terminal.

Install the latest stable version of node (you need Node >= 6):

```sh
nvm install node
```

[Fork the repo](https://github.com/benmvp/react-workshop/fork) and create a local clone (be sure to replace `YOUR-USERNAME` with your own):

```sh
git clone https://github.com/YOUR-USERNAME/react-workshop.git
```

Copy the [`00-begin`](./) directory, name it `workshop`, and change to it:

```sh
cd react-workshop
cp -r 00-begin workshop
cd workshop
```

Install all of the dependencies:

```sh
# Yarn
yarn

# NPM
npm install
```

Start the app:

```sh
# Yarn
yarn start

# NPM
npm start
```

## Tasks

- Visit [http://localhost:3000/](http://localhost:3000/) and you should see an empty page

## Next

Go to [Step 1 - JSX](../01-jsx/).

## Resources

- [Fork A Repo on Github](https://help.github.com/articles/fork-a-repo/)
- [`git-clone`](https://git-scm.com/docs/git-clone)
- [Create React App](https://github.com/facebookincubator/create-react-app)