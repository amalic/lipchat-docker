# lipchat-docker

## Build and Run
### Get the code
```bash
git clone --recursive <this-repository-url>
cd lipchat-docker

```
### Get a prebuilt model
```bash
wget https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing \
  -O lipchat-word2vec/model/GoogleNews-vectors-negative300.bin.gz
```

## Run
```bash
docker-compose up -d
```

## Test
Once the initial build has finished navigate to http://localhost
