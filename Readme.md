# trilium-heroku

deploy [trilium](https://github.com/zadam/trilium) to [heroku](https://heroku.com)

## Usage

### OneKey deploy

[![Deploy](https://www.herokucdn.com/deploy/button.svg)]([https://heroku.com/deploy](https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2F&template=https%3A%2F%2Fgithub.com%2Fqwe795138426%2Ftrilium-heroku))

### manual deploy

1. fork the repo in github
1. Create New App with heroku
1. Change heroku stack to container

    ``` shell
    heroku stack:set container -a <APP Name>
    ```

1. in heroku app deploy tabs, link to gitlab & select your repo.
1. select deploy branchand wait it done.
1. finally, click Open App button, then you'll see the trilium web page.
