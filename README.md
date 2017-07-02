#  TensorFlow™ Docker image


Docker Image for TensorFlow™. This Docker image provides Python, Java, C and Go execution environment.

Provided images :
* [TensorFlow™ 1.2.1 with Python 2.7 CPU](https://github.com/hellgate75/tensiorflow/tree/1.2.1-cp27)


### Introduction ###

TensorFlow™ is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API. TensorFlow was originally developed by researchers and engineers working on the Google Brain Team within Google's Machine Intelligence research organization for the purposes of conducting machine learning and deep neural networks research, but the system is general enough to be applicable in a wide variety of other domains as well.


Here some more info about  TensorFlow™ :
https://www.tensorflow.org/

Here some infromation about  TensorFlow™ develoment :
https://www.tensorflow.org/get_started/


### Goals ###

This docker images has been designed to be a test, development, integration, production environment for  TensorFlow™.
*No warranties for production use.*


### Docker Image features ###

Here some information :

Volumes : /root/tf-app


`/root/tf-app` :

Folder to install sources.


Ports:

None


### H2o™ Sparkling Water® Docker Environment Entries ###

Here TensioFlow® environment variables :

None


### Sample command ###

Here a sample command to run TensiorFlow™ container:

```bash
docker run -d -v my/app/dir:/root/tf-app --name my-tensiorflow hellgate75/tensiorrlow:latest
```


### Test Spark / YARN console ###

In order to access to TensiorFlow™ shell :
```bash
    docker exec -it my-tensiorflow bash
```


### License ###

[LGPL 3](https://github.com/hellgate75/sparkling-water/blob/master/LICENSE)