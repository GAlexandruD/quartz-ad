### Short instructions for the user to get started with Quartz
*Not part of the upstream Quartz*

## Start local server
```sh
npx quartz build --serve --directory ~/Dropbox/0_SecondBrain/_ONLINE_PUBLISHED
```

## Push changes to GitHub
```sh
npx quartz sync
```

## Install dependencies
```sh
npm install
```

## Fetch updates from upstream
```sh
git remote add upstream https://github.com/jackyzha0/quartz.git
git fetch upstream
git branch -r  # check if upstream/v4 is available
git merge upstream/v4
```

