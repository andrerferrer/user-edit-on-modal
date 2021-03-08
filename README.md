# GOAL

This is a demo to show-case how to add a modal in your app to edit the logged in user with the Devise gem and Boostrap.

[You can also check my other demos](https://github.com/andrerferrer/dedemos/blob/master/README.md#ded%C3%A9mos).

## What needs to be done?

1. [Export Devise form to a partial](8584f08).
1. [Add the partial to the page you want to use](https://github.com/andrerferrer/user-edit-on-modal/commit/62f544dee09f1d9ceb8a37f776dc0f92cacdc1de).
1. [Add a modal to the home page](https://github.com/andrerferrer/user-edit-on-modal/commit/50870a0a3e68af7e4476135d9506f4e384b4d848).
1. [Refactor modal into partial](https://github.com/andrerferrer/user-edit-on-modal/commit/eb7d8c83308fb0648c381486a711f60e2466d003).

### If you want to check it locally
```sh
repo_name="user-edit-on-modal"
gh_repository="git@github.com:andrerferrer/$repo_name.git"
git clone $gh_repository demo
cd demo
bundle install
yarn install
rails db:create db:migrate db:seed
rails s

# now you can go to http://localhost:3000/ and check it out
```


And we're good to go 🤓

Good Luck and Have Fun
