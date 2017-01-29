## Blog

This is a monorepo (using lerna) for the blog app built using microapps.

[Learn More](https://github.com/gautamarora/blog/blob/master/README.md)

## How to run

1. Install Lerna

        npm install -g lerna

1. Clone the blog monorepo:

        git clone git@github.com:gautamarora/blog-monorepo.git

1. Install dependencies:

        cd blog-monorepo
        lerna bootstrap

1. Run the blog app:

        lerna run --scope @gautamarora/blog start
        Go to localhost:3000
        
1. Run just the blog posts app:

        lerna run --scope @gautamarora/post start
        Go to localhost:3000/posts

## Live Examples
[www.gautamarora.com](http://www.gautamarora.com)
