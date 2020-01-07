This project is based on article: [Create-React-App Continuous Integration Config with CircleCI](https://medium.com/@eferhatg/create-react-app-continuous-integration-config-with-circleci-and-aws-2b0238cde169) and the example [Repo](https://github.com/facebook/create-react-app)

## Setup requirements

`curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -`
`echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list`
`sudo apt update`
`sudo apt install npm yarn`

## update npm to latest globally

`sudo npm i -g npx`

## clear bash cache to show the update npm version
`hash -d npm`
`npm -v`

Now follow along the instructions from section “New CRA application” in the [Medium article](https://medium.com/@eferhatg/create-react-app-continuous-integration-config-with-circleci-and-aws-2b0238cde169).

**The final working config.yml should look somethine like .circleci/config.yml**



