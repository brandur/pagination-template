# Pagination Example Template

Set-up:

``` bash
git clone https://github.com/brandur/pagination-template
gem install foreman
cd pagination-template
bundle install
foreman start
```

To edit the application being run:

```
vi app.rb
```

## Run Tests

```
bundle exec rake
```

## Database

Optionally, get the database bootstrapped with the following:

``` bash
brew install postgres # or as applicable for system
createdb pagination-template
```

To access the newly created database:

```
psql pagination-template
```
