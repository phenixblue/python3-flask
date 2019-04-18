# python3-flask
[![](https://images.microbadger.com/badges/version/jmsearcy/python3-flask.svg)](https://microbadger.com/images/jmsearcy/python3-flask "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/jmsearcy/python3-flask.svg)](https://microbadger.com/images/jmsearcy/python3-flask "Get your own image badge on microbadger.com")

Bits for building a Python3 based Docker Image with Flask baked in


# Build Image

- Build the image locally

    ```
    $ pipenv update
    $ docker-compose build
    ```

- Push the image to a repository

    ```
    $ docker login
    $ docker tag python3-flask:0.1 jmsearcy/python3-flask:0.1
    $ docker push jmsearcy/imageswap-webhook:0.1
    ```