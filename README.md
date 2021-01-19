# Scaffold for social media app with Ruby on Rails

This project is a simple social platform where users can connect and share posts based on a friendship concept. Very similar to the Facebook concept of friendship, which means one user can send out an invitation to connect to another user, and it's up to the receiving user to accept or reject the friendship request. Friendship is symmetrical

## Built With

- Ruby v2.7.0
- Ruby on Rails v5.2.4
- Devise
- PostgreSQL

## Live Demo

[Live demo](https://frozen-plateau-11747.herokuapp.com)


## Getting Started

To get a local copy up and running follow these simple example steps.

Open your terminal and run these commands
- clone this repository by running `git clone git@github.com:cyonii/ror-social-scaffold.git`
- run `cd ror-social-scaffold`
- run `bundle install`
- run `yarn install`
- run `rails db:migrate`
- you can optionally run `rails db:seed` to populate the database with fake data
- run `rails server` to start the application
- typically the live server will be started at `https://localhost:3000`

### Prerequisites

Ruby: 2.6.3
Rails: 5.2.3
Postgres: >=9.5

### Setup

Instal gems with:

```
bundle install
```

Setup database with:

```
   rails db:create
   rails db:migrate
```

### Github Actions

To make sure the linters' checks using Github Actions work properly, you should follow the next steps:

1. On your recently forked repo, enable the GitHub Actions in the Actions tab.
2. Create the `feature/branch` and push.
3. Start working on your milestone as usual.
4. Open a PR from the `feature/branch` when your work is done.


### Usage

Start server with:

`rails server`

Open `http://localhost:3000/` in your browser.

### Run tests

run `rspec` in the containing folder to run tests the application.

## Authors

👤 **CY Kalu**

- GitHub: [@cyonii](https://github.com/cyonii)
- Twitter: [@theOnuoha](https://twitter.com/theOnuoha)
- LinkedIn: [Silas Kalu](https://www.linkedin.com/in/cyonii/)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!


## 📝 License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.  
