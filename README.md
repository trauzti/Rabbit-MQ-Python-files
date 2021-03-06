# Python code for RabbitMQ tutorials

Here you can find Python code examples from [RabbitMQ
tutorials](http://www.rabbitmq.com/getstarted.html).

To successfully use the examples you will need a running RabbitMQ server.

## Requirements

To run this code you need `pika` library version 0.9.5. To install it run

    pip install -e git+http://github.com/pika/pika.git@v0.9.5#egg=pika-v0.9.5

You may first need to run

    easy_install pip


## Code

[Tutorial one: "Hello World!"](http://www.rabbitmq.com/tutorial-one-python.html):

    python send.py
    python receive.py


[Tutorial two: Work Queues](http://www.rabbitmq.com/tutorial-two-python.html):

    python new_task.py
    python worker.py


[Tutorial three: Publish/Subscribe](http://www.rabbitmq.com/tutorial-three-python.html)

    python receive_logs.py
    python emit_log.py


[Tutorial four: Routing](http://www.rabbitmq.com/tutorial-four-python.html)

    python receive_logs_direct.py
    python emit_log_direct.py


[Tutorial five: Topics](http://www.rabbitmq.com/tutorial-five-python.html)

    python receive_logs_topic.py
    python emit_log_topic.py


[Tutorial six: RPC](http://www.rabbitmq.com/tutorial-six-python.html)

    python rpc_server.py
    python rpc_client.py
