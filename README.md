# Artificien

![Team Photo](https://i.ibb.co/dprzDQZ/team-photo.png)

Artificien is a federated learning marketplace. It connects data scientists looking to train models with app developers that have access to data, and trains such models remotely on-device using Pysyft's federated learning library.

## Architecture
- Frontend code for the Marketplace is stored in the [Artificien Marketplace Repository](https://github.com/dartmouth-cs98/artificien_marketplace). The marketplace is written in react and will be deployed via `surge.sh`.
- Backend code for the Marketplace is stored in the [Artificien Marketplace Backend Repository](https://github.com/dartmouth-cs98/artificien_marketplace_backend). The backend will be run via a severless framework using AWS API Gatway and AWS Lambda, and deployed via the Artificien Infrastructure Repository.
- Code to spawn single-user jupyter servers to allow clients to work with sample data and build their models is stored in the [Artificien Jupyter Repository](https://github.com/dartmouth-cs98/artificien_jupyter). 
- Infrastructure code is stored in the [Artificien Infrastructure Repository](https://github.com/dartmouth-cs98/artificien_infrastructure). The insfrastrucure includes a DynamoDB (NoSQL database) utilized by the Marketplace, the severless backend, and any other cloud resources which may be relevant to the product.
- iOS code stored in [Artificien iOS Repository](https://github.com/dartmouth-cs98/artificien_ios). This will be used for a demo application that stores user data and exposes it to the Artificien platform for learning/analysis.
- Jupyter Notebooks used as test examples to test the federated learning workflow will be stored in the [Artificien Experimental Repository](https://github.com/dartmouth-cs98/artificien_experimental)

## Setup

TODO: how to get the project dev environment up and running, npm install etc, all necessary commands needed, environment variables etc

## Deployment

TODO: how to deploy the project

## Authors

* Shreyas Agnihotri '21
* Jake Epstein '21
* Matthew Kenney '21
* Tobias Lange '21
* Alexander Quill '21

## Acknowledgments
