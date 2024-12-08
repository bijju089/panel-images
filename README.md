## Pelican/Pterodactyl/WISP Docker Images

Docker images that can be used with the Pelican/Pterodactyl/WISP Game Panel. You can request more images by opening a new issue. These are mostly created for myself.

Additional Pterodactyl images can be found at [Pelican Yolks](https://github.com/pelican-eggs/yolks), [Pterodactyl Yolks](https://github.com/pterodactyl/yolks).

## How to add image to your egg

Navigate to `Admin Panel -> Nests -> Select your egg`. Add Docker image URL(s) from the [available list](https://github.com/bijju089/panel-images#pterodactylwisp-images) into the Docker Images section.

![image](https://user-images.githubusercontent.com/10975908/120903180-56719d80-c64d-11eb-8666-02de8ea80701.png)

### Supported Platforms

| Image                                                                                                  | Supported platforms |
| ------------------------------------------------------------------------------------------------------ | ------------------- |
| [Java Azul Zulu](https://github.com/bijju089/panel-images#java-azul-zulu-amd64arm64)             | AMD64, ARM64        |
| [Java GraalVM](https://github.com/bijju089/panel-images#java-graalvm-amd64arm64)                 | AMD64, ARM64        |
| [Java OpenJ9](https://github.com/bijju089/panel-images#java-openj9-amd64)                        | AMD64               |
| [Node.js](https://github.com/bijju089/panel-images#nodejs-amd64arm64)                            | AMD64, ARM64        |
| [Python](https://github.com/bijju089/panel-images#python-amd64arm64)                             | AMD64, ARM64        |  


### Java Azul Zulu [AMD64/ARM64]

- [Java 8 Zulu](https://github.com/bijju089/panel-images/tree/main/java-zulu/8)
  - `ghcr.io/bijju089/panel-images:java_8_zulu`
- [Java 11 Zulu](https://github.com/bijju089/panel-images/tree/main/java-zulu/11)
  - `ghcr.io/bijju089/panel-images:java_11_zulu`
- [Java 16 Zulu](https://github.com/bijju089/panel-images/tree/main/java-zulu/16)
  - `ghcr.io/bijju089/panel-images:java_16_zulu`
- [Java 17 Zulu](https://github.com/bijju089/panel-images/tree/main/java-zulu/17)
  - `ghcr.io/bijju089/panel-images:java_17_zulu`
- [Java 18 Zulu](https://github.com/bijju089/panel-images/tree/main/java-zulu/18)
  - `ghcr.io/bijju089/panel-images:java_18_zulu`
- [Java 19 Zulu](https://github.com/bijju089/panel-images/tree/main/java-zulu/19)
  - `ghcr.io/bijju089/panel-images:java_19_zulu`
- [Java 20 Zulu](https://github.com/bijju089/panel-images/tree/main/java-zulu/20)
  - `ghcr.io/bijju089/panel-images:java_20_zulu`
- [Java 21 Zulu](https://github.com/bijju089/panel-images/tree/main/java-zulu/21)
  - `ghcr.io/bijju089/panel-images:java_21_zulu`
- [Java 22 Zulu](https://github.com/bijju089/panel-images/tree/main/java-zulu/22)
  - `ghcr.io/bijju089/panel-images:java_22_zulu`

### Java GraalVM [AMD64/ARM64]

**NOTE**: Java 8 is AMD64 only due to lack of support from upstream

- [Java 8 GraalVM-CE](https://github.com/bijju089/panel-images/tree/main/java-graalvm/8)
  - `ghcr.io/bijju089/panel-images:java_8_graalvm`
- [Java 11 GraalVM JDK](https://github.com/bijju089/panel-images/tree/main/java-graalvm/11)
  - `ghcr.io/bijju089/panel-images:java_11_graalvm`
- [Java 17 GraalVM JDK](https://github.com/bijju089/panel-images/tree/main/java-graalvm/17)
  - `ghcr.io/bijju089/panel-images:java_17_graalvm`
- [Java 21 GraalVM JDK](https://github.com/bijju089/panel-images/tree/main/java-graalvm/21)
  - `ghcr.io/bijju089/panel-images:java_21_graalvm`
- [Java 22 GraalVM JDK](https://github.com/bijju089/panel-images/tree/main/java-graalvm/22)
  - `ghcr.io/bijju089/panel-images:java_22_graalvm`

### Java OpenJ9 [AMD64]

- [Java 8 OpenJ9](https://github.com/bijju089/panel-images/tree/main/java-openj9/8)
  - `ghcr.io/bijju089/panel-images:java_8_openj9`
- [Java 11 OpenJ9](https://github.com/bijju089/panel-images/tree/main/java-openj9/11)
  - `ghcr.io/bijju089/panel-images:java_11_openj9`
- [Java 16 OpenJ9](https://github.com/bijju089/panel-images/tree/main/java-openj9/16)
  - `ghcr.io/bijju089/panel-images:java_16_openj9`
- [Java 17 OpenJ9](https://github.com/bijju089/panel-images/tree/main/java-openj9/17)
  - `ghcr.io/bijju089/panel-images:java_17_openj9`
- [Java 18 OpenJ9](https://github.com/bijju089/panel-images/tree/main/java-openj9/18)
  - `ghcr.io/bijju089/panel-images:java_18_openj9`
- [Java 20 OpenJ9](https://github.com/bijju089/panel-images/tree/main/java-openj9/20)
  - `ghcr.io/bijju089/panel-images:java_20_openj9`
- [Java 21 OpenJ9](https://github.com/bijju089/panel-images/tree/main/java-openj9/21)
  - `ghcr.io/bijju089/panel-images:java_21_openj9`

### Node.js [AMD64/ARM64]

- [Nodejs 12](https://github.com/bijju089/panel-images/tree/main/nodejs/12)
  - `ghcr.io/bijju089/panel-images:nodejs_12`
- [Nodejs 14](https://github.com/bijju089/panel-images/tree/main/nodejs/14)
  - `ghcr.io/bijju089/panel-images:nodejs_14`
- [Nodejs 15](https://github.com/bijju089/panel-images/tree/main/nodejs/15)
  - `ghcr.io/bijju089/panel-images:nodejs_15`
- [Nodejs 16](https://github.com/bijju089/panel-images/tree/main/nodejs/16)
  - `ghcr.io/bijju089/panel-images:nodejs_16`
- [Nodejs 17](https://github.com/bijju089/panel-images/tree/main/nodejs/17)
  - `ghcr.io/bijju089/panel-images:nodejs_17`
- [Nodejs 18](https://github.com/bijju089/panel-images/tree/main/nodejs/18)
  - `ghcr.io/bijju089/panel-images:nodejs_18`
- [Nodejs 19](https://github.com/bijju089/panel-images/tree/main/nodejs/19)
  - `ghcr.io/bijju089/panel-images:nodejs_19`
- [Nodejs 20](https://github.com/bijju089/panel-images/tree/main/nodejs/20)
  - `ghcr.io/bijju089/panel-images:nodejs_20`
- [Nodejs 21](https://github.com/bijju089/panel-images/tree/main/nodejs/21)
  - `ghcr.io/bijju089/panel-images:nodejs_21`
- [Nodejs 22](https://github.com/bijju089/panel-images/tree/main/nodejs/22)
  - `ghcr.io/bijju089/panel-images:nodejs_22`

### Python [AMD64/ARM64]

- [Python 2.7](https://github.com/bijju089/panel-images/tree/main/python/2.7)
  - `ghcr.io/bijju089/panel-images:python_2.7`
- [Python 3.6](https://github.com/bijju089/panel-images/tree/main/python/3.6)
  - `ghcr.io/bijju089/panel-images:python_3.6`
- [Python 3.7](https://github.com/bijju089/panel-images/tree/main/python/3.7)
  - `ghcr.io/bijju089/panel-images:python_3.7`
- [Python 3.8](https://github.com/bijju089/panel-images/tree/main/python/3.8)
  - `ghcr.io/bijju089/panel-images:python_3.8`
- [Python 3.9](https://github.com/bijju089/panel-images/tree/main/python/3.9)
  - `ghcr.io/bijju089/panel-images:python_3.9`
- [Python 3.10](https://github.com/bijju089/panel-images/tree/main/python/3.10)
  - `ghcr.io/bijju089/panel-images:python_3.10`
- [Python 3.11](https://github.com/bijju089/panel-images/tree/main/python/3.11)
  - `ghcr.io/bijju089/panel-images:python_3.11`
- [Python 3.12](https://github.com/bijju089/panel-images/tree/main/python/3.12)
  - `ghcr.io/bijju089/panel-images:python_3.12`
- [Python 3.13-rc](https://github.com/bijju089/panel-images/tree/main/python/3.13-rc)
  - `ghcr.io/bijju089/panel-images:python_3.13-rc`
