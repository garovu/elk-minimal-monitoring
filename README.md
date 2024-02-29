# ELK Cluster using Docker Compose

This repository contains the Docker Compose configuration to set up an ELK (Elasticsearch, Logstash, Kibana) cluster for centralized logging.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/garovu/elk-minimal.git
    ```

2. Navigate to the cloned directory:

    ```bash
    cd elk-cluster
    ```

3. Start the ELK cluster:

    ```bash
    docker-compose up -d
    ```

4. Access Kibana:

    Open your web browser and go to [http://localhost:5601](http://localhost:5601)

## Configuration

The Docker Compose file (`docker-compose.yml`) defines the configuration for the ELK cluster. You can customize the configuration as needed.

## Usage

- Elasticsearch: Available at [http://localhost:9200](http://localhost:9200)
- Logstash: Container is configured to listen for input on port 5000 by default.
- Kibana: Available at [http://localhost:5601](http://localhost:5601)

## Important Notes

- Make sure to adjust the Docker resources allocated to each container based on your system requirements.
- This setup is intended for development and testing purposes. Consider additional security measures before deploying to production.

## Contributing

Feel free to contribute to this project by submitting pull requests or raising issues.

## License

This project is licensed under the [MIT License](LICENSE).
