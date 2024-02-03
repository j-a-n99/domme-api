# README

## Commands:

create a project:

`rails new domme-api -J --api –d sqlite3 --skip-test`
> -J: skip javascript 
> 
> --api: lightweight API only build
> 
> -d: Database
> 
> --skip-test: no tests

create a model:

`rails g scaffold Post title:string body:text --api`
> Post: Model name
> 
> title:string: param:type
> 
> --api: no html responses


setup:

`bundle install`

`rails db:create db:migrate`

`rails s -p 3000`
