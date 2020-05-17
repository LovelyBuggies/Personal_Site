# README

This repo is built for my personal academic website, generated with [Hugo](https://gohugo.io/) and [Mainroad](https://github.com/Vimux/Mainroad/) theme.

## Usage

```bash
hugo new site quickstart
mv ./quickstart/* ./Personal_Site/
cd ./script
hugo -D
hugo --theme="mainroad" --baseUrl="https://lovelybuggies.com.cn/Personal_Site/"
mv ./public/* ../
```

