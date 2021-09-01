# Oinam CDN

[![Netlify Status](https://api.netlify.com/api/v1/badges/721ee4c3-d7bc-4ce1-be1d-3c9f2bfd6345/deploy-status)](https://app.netlify.com/sites/oinam-cdn/deploys)

URL: cdn.oinam.com

Updated and regularly used digital assets by Oinam Online Properties.
Needs to be globally distributed and highly available.

## Git

List Git-LFS

$ git lfs ls-files --all

## Netlify

SiteName > Site settings > Build & deploy > Environment

Click the "Edit variables" and set "GIT_LFS_ENABLED" as key and "true" as value.

## Images

Convert Images to WEBP using `cwebp`
https://web.dev/codelab-serve-images-webp/

Single File
`cwebp -q 80 file.jpg -o file.webp`

Multiple files in recursive folders
`for file in img/*/*; do cwebp -q 80 "$file" -o "${file%.*}.webp"; done`