# AWS Elastic Beanstalk Sample Templates

A ```Dockerrun.aws.json``` file is an Elastic Beanstalk–specific JSON file that describes how to deploy a set of Docker containers as an Elastic Beanstalk application. You can use a ```Dockerrun.aws.json``` file for a multicontainer Docker environment (templates v2).

```Dockerrun.aws.json``` describes the containers to deploy to each container instance in the environment as well as the data volumes to create on the host instance for the containers to mount.

A ```Dockerrun.aws.json``` file can be used on its own or zipped up with additional source code in a single archive. Source code that is archived with a Dockerrun.aws.json is deployed to container instances and accessible in the /var/app/current/ directory. Use the volumes section of the config to provide mount points for the containers running on the instance, and the mountPoints section of the embedded container definitions to mount them from the containers.

[Elastic Beanstalk v2] (http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker_v2config.html)

[Elastic Beanstalk v1] (http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker_image.html)
