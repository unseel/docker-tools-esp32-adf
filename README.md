# Build esp-adf using docker


## Steps

1. Run the docker container

```sh
docker run -it --rm robbietree/esp32-adf-build-kit:0.0.1
```

2. Change directory

```sh
cd $ADF_PATH/examples/get-started/play_mp3_control
```

3. Config

```sh
idf.py set-target esp32
idf.py menuconfig
```

4. Build

```sh
idf.py build
```

