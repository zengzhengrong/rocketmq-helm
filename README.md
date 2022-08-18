# Getting started with rocketmq-helm

This mode is ```2m-2s-async```.

## Pulling rocketmq-helm

There are two different ways to install rocketmq by helm.

- ```git clone```:

    ```bash
    # git clone https://github.com/sunnyzhy/rocketmq-helm.git rocketmq

    # helm package rocketmq
    
    # rm -rf ./rocketmq/charts/README.md
    
    # helm package rocketmq

    # helm install rocketmq-cluster rocketmq-4.9.4.tgz
    ```

- ```wget```:

    ```bash
    # wget https://github.com/sunnyzhy/rocketmq-helm/releases/download/4.9.4/rocketmq-4.9.4.tgz

    # helm install rocketmq-cluster rocketmq-4.9.4.tgz
    ```

## View rocketmq dashboard

- url: ```http://<host or ip>:30080/```
- ```username/password: admin/admin```
