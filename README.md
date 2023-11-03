# Oinam CDN

URL: `cdn.oinam.com`

> Updated and regularly used digital assets by Oinam online properties. Needs to be globally distributed and highly available.

## Git

List Git-LFS

$ git lfs ls-files --all

## Cloudflare

SiteName > Site settings > Build & deploy > Environment

Click the "Edit variables" and set "GIT_LFS_ENABLED" as key and "true" as value.

## Powered by

([Render](https://render.com) is a also good alternative to consider.)

- 2020-2021: Netlify
- 2022-20xx: Github > Cloudflare Pages

### Notes

- Cloudflare Pages only supports files up to 26.2MB.