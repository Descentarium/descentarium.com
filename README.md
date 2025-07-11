# Descentarium

This is jekyll files for the site descentarium.com


Here is how you can run it locally:

```sh
jekyll serve
```

Here is how to build it and deploy:


```sh
jekyll build
cp -r _site/* ../descentarium.com
cd ../descentarium.com
git add .
git commit -m "v0.01" # Replace with your version
git push origin master
```
