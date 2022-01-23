## Supported tags and respective Dockerfile links

#### Tags:

- [java17-latest](https://hub.docker.com/layers/zapp88/graalvm-multiarch/java17-latest/images/sha256-de3c22c967aafd461395457f357a3b6e3ca26d30e2bf411edf733a179a1ac788?context=repo)
- [java17-mandrel21.3.0](https://hub.docker.com/layers/zapp88/graalvm-multiarch/java17-graalvm21.3.0/images/sha256-de3c22c967aafd461395457f357a3b6e3ca26d30e2bf411edf733a179a1ac788?context=repo)
- [java11-latest](https://hub.docker.com/layers/zapp88/graalvm-multiarch/java11-latest/images/sha256-dda3e9c5d343225ef4dc5b81ce29d07fec6bc9b45965d90cf87b8707ef21d155?context=repo)
- [java11-mandrel21.3.0](https://hub.docker.com/layers/zapp88/graalvm-multiarch/java11-graalvm21.3.0/images/sha256-4b4e921930883c6387ce3f91b3915a714a614e19edb0f03cad778cc00a217940?context=repo)
- [arm64-java17-mandrel21.3.0](https://hub.docker.com/layers/zapp88/graalvm-multiarch/arm64-java17-graalvm21.3.0/images/sha256-d70d7d5b513c006d41f6275d3f669551d120cd8debc903f8daadf3ed2fb3421f?context=repo)
- [amd64-java17-mandrel21.3.0](https://hub.docker.com/layers/zapp88/graalvm-multiarch/amd64-java17-graalvm21.3.0/images/sha256-de3c22c967aafd461395457f357a3b6e3ca26d30e2bf411edf733a179a1ac788?context=repo)
- [amd64-java11-mandrel21.3.0](https://hub.docker.com/layers/zapp88/graalvm-multiarch/amd64-java11-graalvm21.3.0/images/sha256-4b4e921930883c6387ce3f91b3915a714a614e19edb0f03cad778cc00a217940?context=repo)
- [arm64-java11-mandrel21.3.0](https://hub.docker.com/layers/zapp88/graalvm-multiarch/arm64-java11-graalvm21.3.0/images/sha256-dda3e9c5d343225ef4dc5b81ce29d07fec6bc9b45965d90cf87b8707ef21d155?context=repo)

#### Why no ':latest' tag ?

This image is provided in 3 differing versions
(different java version)-(different architecture)-(different version) since the choice of java version should be explicit we only provide java17-latest and java11-latest.

#### Dockerfile:

<https://raw.githubusercontent.com/zapp88/graalvm-multiarch/master/Dockerfile>

#### Where to file issues:

<https://github.com/zapp88/graalvm-multiarch/issues>

Supported architectures: amd64, arm64v8

## What is GraalVM?

GraalVM is a high-performance JDK distribution designed to accelerate the execution of applications written in Java and other JVM languages along with support for JavaScript, Ruby, Python, and a number of other popular languages.

The project website at https://www.graalvm.org/ describes how to get started, how to stay connected, and how to contribute.

## License

View license information for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
