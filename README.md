# Neuro Pos API

## Setup

  - Get the code

```
git clone git@bitbucket.org:hashdogteam/neuro_pos_api.git
```

  - Install dependencies

```
cd neuro_pos_api
dep install
```

  - Install test's dependencies

```
cd neuro_pos_api
dep install -f .gems-test
```

## Launch

```
cd neuro_pos_api
rackup
```

## Testing

```
rake test:all      # Run tests for all
rake test:libs     # Run tests for libs
rake test:models   # Run tests for models
rake test:routes   # Run tests for routes
```

## Benchmarking

```
rake bench         # Run benchs tests for all
rake bench:all     # Run tests for all
rake bench:routes  # Run tests for routes
```