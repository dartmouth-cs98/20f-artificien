# Artificien

![Team Photo](https://i.ibb.co/8XQYpjZ/artificien-logo.png)

Artificien is a federated learning marketplace. It connects data scientists looking to train models with app developers that have access to data, and trains such models remotely on-device using Pysyft's federated learning library.

## Architecture

- Frontend code for the Marketplace is stored in the [Artificien Marketplace Repository](https://github.com/dartmouth-cs98/artificien_marketplace). The marketplace is written in React and continuously deployed via AWS Amplify.
- Code to spawn single-user jupyter servers to allow clients to work with sample data and build their models is stored in the [Artificien Jupyter Repository](https://github.com/dartmouth-cs98/artificien_jupyter). 
- Infrastructure code is stored in the [Artificien Infrastructure Repository](https://github.com/dartmouth-cs98/artificien_infrastructure). The infrastructure includes a DynamoDB (NoSQL database) utilized by the Marketplace, the severless backend, an AWS Amplify deployment which is used to continuously deploy the frontend in [Artificien Marketplace Repository](https://github.com/dartmouth-cs98/artificien_marketplace) and connect it to associated backend resources. The infrastructure repository also deploys AWS Cognito, a service which allows our users to sign up and sign in to the website.
- The iOS cocoapod for app developers to integrate their app with Artificien is stored in the [Artificien iOS Library Repository](https://github.com/dartmouth-cs98/artificien_ios_library)
- iOS code is stored in the [Artificien iOS Repository](https://github.com/dartmouth-cs98/artificien_ios). This is a demo application that stores a user's Apple Health data and exposes it to the Artificien platform for learning/analysis through the CocoaPod.
- Jupyter Notebooks used as test examples to test the federated learning workflow are stored in the [Artificien Tutorials Repository](https://github.com/dartmouth-cs98/artificien_tutorials)
- Fake data generations to provide sample data to users and notebooks containing various custom federated learning optimizers and other R&D notebooks is in [Artificien Experimental Repository](https://github.com/dartmouth-cs98/artificien_experimental)
- Artificien's master node service that orchestrates federated learning for multiple apps and users is in [Artificien Orchestration Node Repository](https://github.com/dartmouth-cs98/artificien_orchestration_node)
- Artificien's python library for building pytorch models compatible with federated learning and Artificien's infrastructure [Artificien Python Library](https://github.com/dartmouth-cs98/artificien_python_library)
- Artificien's edits to pygrid service, the open source library that underpins our federated learning implementation is in [Artificien PyGrid Fork](https://github.com/dartmouth-cs98/artificien_pygrid_fork)

## Setup & Deployment

Please see each of the individual repositories for details about their development.

## Authors

* Shreyas Agnihotri '21
* Jake Epstein '21
* Matthew Kenney '21
* Tobias Lange '21
* Alexander Quill '21

## Acknowledgments

Thank you to Tim Tregubov for his guidance during this course project and to the team at OpenMined for their tireless work on the federated learning libraries used by this platform.
