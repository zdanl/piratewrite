> Piratewrite is an Appwrite.io fork meant to support fiat and cryptocurrency payment natively, as well, scale to millions rather than thousands, with limits max.'ed out of the box ☁️🎉

![cyberpunk_lesbian_duo](https://github.com/zdanl/piratewrite/assets/114028070/d034b033-dea5-4980-8581-a2ba4f2d0b8d)


<br />
<p align="center">
    <a href="https://appwrite.io" target="_blank"><img src="./public/images/banner.png" alt="Appwrite Logo"></a>
    <br />
    <br />
    <b>Appwrite is a backend platform for developing Web, Mobile, and Flutter applications. Built with the open source community and optimized for developer experience in the coding languages you love.</b>
    <br />
    <br />
</p>

### Unix

```bash
docker run -it --rm \
    --volume /var/run/docker.sock:/var/run/docker.sock \
    --volume "$(pwd)"/appwrite:/usr/src/code/appwrite:rw \
    --entrypoint="install" \
    appwrite/appwrite:1.4.12
```

