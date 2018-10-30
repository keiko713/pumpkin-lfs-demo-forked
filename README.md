# pumpkin-lfs-demo

1. fork the repo! and clone the forked repo locally
2. with the local cloned repo dir, run `netlify init`
   - this will create a new Netlify site with this repo
3. provision netlify lfs addon: `netlify addons:create netlify-lfs-staging`
4. setup the lfs! run: `netlify lfs:setup`
   - you may be scolded if you don't have the lfs installed in your laptop
   - this example has two jpg images, so specify `*.jpg` with `Specify which files you want to track (optional)` question
5. run `git commit -am 'Enable Netlify LFS feature'`
6. run `git push origin master`
   - this will trigger the automatic deploy!
7. checkout the site! it should be using LFS. I hope.
