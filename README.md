# 🐙 GitHub Followers Tracker

![Build Status](https://github.com/AnandChowdhary/followers-tracker/workflows/GitHub%20Followers%20Tracker/badge.svg)

This repo uses GitHub Actions to track a list of my followers on GitHub, and posts updates on Slack. It's largely based on [plibither8/gh-followers-tracker](https://github.com/plibither8/gh-followers-tracker), and runs every two hours.

![Screenshot of Slack channel](https://github.com/AnandChowdhary/followers-tracker/blob/master/screenshot.png?raw=true)

## ⭐ Usage

Required environment variables:

- `GIST_ID` is the ID of a GitHub Gist containing a list of followers
- `GH_TOKEN` is a GitHub personal access token with the `gist` scope

## 📄 License

- [MIT](./LICENSE) © [Anand Chowdhary](https://anandchowdhary.com)
- Original repo: [plibither8/gh-followers-tracker](https://github.com/plibither8/gh-followers-tracker)
