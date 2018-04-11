# Accelerate blog

## To generate

```
hexo generate
```

## To test locally

```
hexo serve
```

or

Run `public/index.html` using IntelliJ

## To deploy

Change the `url` field in `_config.yml` to point to `http://blog.accelerate.io`

Generate the static page again
```
hexo generate
```

Sync the public folder:

```
cd public
aws s3 sync s3://blog.accelerate.io
```