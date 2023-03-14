# 🌳 Auto Commit

Making green your Github stats, powered by [Github Actions](https://github.com/features/actions)

[![Auto Commit](https://github.com/madfauzy/Auto-Commit/actions/workflows/autocommit.yml/badge.svg)](https://github.com/madfauzy/Auto-Commit/actions/workflows/autocommit.yml)

## Make it your own

- Create your own repo with click "**Use this template**" button (forked repo will not work)

Or just do in the manual way:

- Create your own repo
- Copy file `.github/workflows/autocommit.yml` and `LAST_UPDATED` to your repo
- Change the `name` and `email` information on file [autocommit.yml, line 27 and 28](https://github.com/madfauzy/Auto-Commit/blob/main/.github/workflows/autocommit.yml#L27)
- Change the scheduling time on file [autocommit.yml, line 9](https://github.com/madfauzy/Auto-Commit/blob/main/.github/workflows/autocommit.yml#L9). You can use [crontab.guru](https://crontab.guru/) if you are not familiar with the cron schedule string. For first time, you can try to run it in every hour with string `1 * * * *` .
- Consider to support me, at least click the 🌟 button

## Article (in Bahasa Indonesia)

- <https://mazipan.space/membuat-commit-otomatis-ke-github/>

## Credits

- [Github Actions](https://github.com/features/actions)
- [ad-m/github-push-action](https://github.com/ad-m/github-push-action)
- [Irfan Maulana](https://github.com/mazipan)
