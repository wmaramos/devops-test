## Pré-requisitos
* ruby 2.6.4
* bundler 1.17.3

## Instalar dependencias
`bundle install --path vendor`

## Unit Tests
`bundle exec rails test`

## Security Tests
`bundle exec brakeman`

## Como iniciar
**Variavéis de ambiente**
```
RAILS_MAX_THREADS=5
PORT=3000
```

**Start do server**
`bundle exec rails server`
