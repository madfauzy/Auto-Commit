# 🌳 Auto Commit

Making green your Github stats, powered by [Github Actions](https://github.com/features/actions)

[![Auto Commit](https://github.com/madfauzy/Auto-Commit/actions/workflows/autocommit.yml/badge.svg)](https://github.com/madfauzy/Auto-Commit/actions/workflows/autocommit.yml)

## Make it your own

- Create your own repository by clicking the "**Use this template**" button (please note that using a forked repository will not work)

Alternatively, you can manually create it by following these steps:

- Create your own repository
- Copy the files `.github/workflows/autocommit.yml` and `LAST_UPDATED` to your repository
- Update the `name` and `email` information in the [autocommit.yml](https://github.com/madfauzy/Auto-Commit/blob/main/.github/workflows/autocommit.yml#L27), specifically on lines 27 and 28
- Adjust the scheduling time in the [autocommit.yml](https://github.com/madfauzy/Auto-Commit/blob/main/.github/workflows/autocommit.yml#L9), found on line 9. If you're not familiar with the cron schedule string, you can use [crontab.guru](https://crontab.guru/) to help. For the first time, you can try to run it in every hour with string `1 * * * *`.
- Please show your support for [Irfan Maulana](https://github.com/mazipan) by visiting the [auto-commit](https://github.com/mazipan/auto-commit) repository and at least click the 🌟 button

## Article (in Bahasa Indonesia)

- <https://mazipan.space/membuat-commit-otomatis-ke-github/>

## Credits

- [Github Actions](https://github.com/features/actions)
- [ad-m/github-push-action](https://github.com/ad-m/github-push-action)
- [Irfan Maulana](https://github.com/mazipan)
