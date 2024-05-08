# felk-container-demo
Docker Compose setup for a demo Elastic Stack with Fleet

:warning: This is not an Elastic created, sponsored, or maintained project. Elastic is not responsible for this projects design or implementation.

[![elastic-container.png](https://i.postimg.cc/J7TpsqKJ/elastic-container.png)](https://postimg.cc/NLH6VR3f)

## Steps

1. `Git clone` this repo
2. Install docker compose or podman compose
3. Change into the `felk-container-demo/` folder
4. Change the various secrets in the `.env` file
5. Execute `docker compose up -d` or `docker-compose up -d` or `podman compose up -d`.
Kibana will use a self-signed certificate. You may need to type `thisisnotsafe` or click to proceed past the warning to the log in screen.
