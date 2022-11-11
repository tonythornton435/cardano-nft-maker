<h1 align="center">Welcome to cardano-nft-maker 👋</h1>

> A cardano-nft maker for my diploma thesis

## Requirements

The application requires [docker](https://www.docker.com/products)
and [docker-compose](https://docs.docker.com/compose/install/) utility. It is also recommended that you run it from
Linux or under WSL2 if you are on Windows.

## Development

For development, you can use the following script which setups cardano-node and opens up a shell with a backend server.
It might take some time at first , because the whole chain needs to sync

```sh
chmod +x ./run_backend_dev_environment.sh
./run_backend_dev_environment.sh
```

## Running

To run the entire app altogether first copy all the private keys from the specific environment to the appropriate file
in [keys](keys) directory, then run the following script.

```sh
chmod +x ./run_backend_dev_environment.sh
./run_solution.sh
```

