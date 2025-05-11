# Custom Ghost Theme

Based on the Ghost Headline theme.

# Development

## Local Commands

- `gulp build` to build the site (apply css and js changes)
- `gulp zip` to zip the site for upload to ghost

## Local Development

- Create a new Ghost site with `ghost install local`
- Run `ghost start` to start ghost
- Go to ghost admin and choose `headline` as the theme
- Inside the `/contents/themes` folder delete the existing `headline` folder
- Create a symbolic link inside `themes` named `headline` and pointing to this repo locally
- Now all local changes will be visible in the ghost site. Remember that for changes to css you need to rebuild.


## Copyright & License

Copyright (c) 2013-2025 Ghost Foundation - Released under the [MIT license](LICENSE).
