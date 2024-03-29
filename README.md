# github-star-reminder

Original Repo: https://github.com/Molunerfinn/github-stars-reminder

Use GitHub actions to email me and tell me the count of stars in my repositories every day.

It will also build a simple page for me to checkout. See: https://tonngw.com/github-star-reminder/

It' a repository for learning GitHub Actions.

## Note

### Run with GitHub Actions

If you fork the repo, you should add the following env value to GitHub [secrets](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/creating-and-using-encrypted-secrets).

Setings -> Secrets -> Actions -> New repository secret

Add these key and value:

```env
GH_TOKEN=
GH_USER=
MAIL_USER=
MAIL_PASS=
MAIL_HOST=
MAIL_PORT=
MAIL_FROM=
MAIL_TO=
# 0 < TOP_NUMBER < 100
TOP_NUMBER=
```

### Run in locally

When you run this repo locally, you should create a `.env` file with all the environment variables above like the [.env.example](/.env.example).

## License

[MIT](http://opensource.org/licenses/MIT)
