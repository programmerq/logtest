This was build with the following:

    $ docker build -t programmerq/logtest .

To run it, do this:

    $ docker run --name logtest -d programmerq/logtest
    f4663339103b6f0f5ea2c9f62fa3dc3c40068022af0d9b459e9ec92480d2a765

To check logs, do this:

    $ docker logs logtest
    hello world

Cleanup:

    $ docker rm logtest

