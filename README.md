# Install


Make sure you are using __Ruby 2.1.1__ ...

rvm: `rvm use 2.1.1`
rbenv: `rbenv rehash`


```
git clone https://github.com/empirical-org/CoFactor.git
```
```
cd cofactor
```
```
bundle
```
```
rake db:migrate
```
```
rails s
```

### Troubleshooting

1. __Can't install 'pg' bundle.__ Either install postgres `brew install postgres` or comment out the `gem 'pg'` line in the Gemfile. CoFactor uses sqlite locally.