# zyb0t-launcher

## Table of Contents

- [Usage](#usage)


### Prerequisites


```
Docker
and/or
Yarn/NodeJS
```

### Installing

Clone the repository locally, enter its directory.

Gunbot will launch and be visible at port 3001 on your local machine. To alter this, inside docker-compose.yml change the ports. 
```yml
    ports: 
      - 3001:5000
```
```sh
# Shared volume
/data/gunthy_linux 
```
## Usage <a name = "usage"></a>
Launching the bundle.
This will generate a container, inside it, will be a gunbot container and zyb0t container. 
They share :

``` docker compose -f 'docker-compose.yml' up -d --build ```

