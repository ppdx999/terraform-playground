# Terraform Playground

# Setup

### Install Terraform

See official document

### Load Env Var

```terminal
export $(cat .env | xargs)
```


# Visualize dependency graph

```terminal
terraform graph | dot -Tsvg > graph.svg
```
