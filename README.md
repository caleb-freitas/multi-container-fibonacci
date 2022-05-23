<h1 align="center">multi-container-pipeline</h1>

## Project

A multi-container application with Docker created to calculate the fibonacci number and persist the data in a PostgreSQL database and use cache with Redis

## How to execute

- Clone the repository `git clone git@github.com:caleb-freitas/travel-control.git`

- Go to the folder that was cloned: `cd travel-control`

- Setup AWS Elastic Beanstalk, RDS, ElastiCache and Nginx to deploy the application

- Run [`git push origin main`](./.github/workflows/deployment.yaml) to trigger the deployment script built with GitHub Actions

## Technologies

- [Docker](https://www.docker.com/)
- [AWS RDS](https://aws.amazon.com/free/database/)
- [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
- [AWS ElastiCache](https://aws.amazon.com/elasticache/)
- [Nginx](https://www.nginx.com/)
