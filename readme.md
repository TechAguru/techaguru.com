# TechAguru website documentation

## Hugo
The website uses [Hugo](https://gohugo.io/) website static generator.
The fastest way to install Hugo is to install [Homebrew](http://brew.sh/).

## Create Static website
```hugo serve --theme=landing-page-hugo --renderToDisk```

## Google Cloud Storage Bucket
The website is hosted on Google Cloud Storage bucket. 

```gsutil rsync -R ~Desktop/techaguru.com/public gs://www.techaguru.com```
