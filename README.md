Citizen
===========
A first step for making your city a better place

Citizen aims to be the go-to app to report what we could call administrative failures such as potholes, broken street lights, uncollected trash and other issues of the sort that should be getting fixed by the government.

## Getting started

### 0. Setup your enviroment
If you don't have a Ruby on Rails environment setup, you can set it up with this amazing guide by the GoRails team:

https://gorails.com/setup/ubuntu/19.10

### 1. Fork the project
Fork the main repository.
Clone your fork and add the main repository as a remote
```
git clone https://github.com/<YOUR_GITHUB_USERNAME>/citizen.git
cd citizen
git remote add citizen https://github.com/upwardbinkie/citizen.git
git fetch citizen
```

Optionally, create a branch you want to work on.

### 2. Get it running locally

- Install gem dependencies with `bundle install`
- Because we're using webpack, run `yarn install --check files` to install our dependencies.
- Run `rails db:create` to create our Postgresql database and then run the migrations with `rails db:migrate`
- Start the app with `rails s` and navigate to http://localhost:3000/ in your browser.
- Again, because we're using webpack you should run `bin/webpack-dev-server` on another terminal to automatically compile js and css files.

If everything went right, you should be looking at something like this:

![Citizen](https://user-images.githubusercontent.com/804175/73229930-281eac80-4141-11ea-82f4-a0f8672e9696.png)

### 5. Done!
You can now start working on whatever feature or issue you'd like and submit a Pull Request when you think it's ready.
