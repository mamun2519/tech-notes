### What is docker?

⇒ **a software platform that allows developers to create, test, and deploy applications in containers**

. Containers are standardized units that contain everything an application needs to run, including code, libraries, and runtime.

### How does Docker Work?

- Docker provides a standard way to run code.
- Docker containers virtualize the operating system of a server.
- Docker containers are lightweight and can run on a single physical server.
- Docker containers can be shared between developers.
- Docker registries are repositories for Docker images.

**Benefits**

- Docker simplifies the development and delivery of applications.
- Docker allows developers to separate their applications from their infrastructure.
- Docker reduces the delay between writing code and running it in production.

**Use cases**

- Docker is used in microservices, continuous integration, and deployment.
- Docker can be used to build, ship, and run distributed applications at any scale.

## Docker Basic Command

**IMAGES
⇒** Docker images are a lightweight, standalone, executable package
of software that includes everything needed to run an application:
code, runtime, system tools, system libraries and settings.

- Build an Image from a Dockerfile

⇒ docker build -t <image_name> .

- Build an Image from a Dockerfile without the cache

⇒ docker build -t <image_name> . –no-cache

- List local images

⇒ docker images

- Delete an Image

⇒ docker rmi <image_name>

- Remove all unused images

⇒docker image prune
