# mongo-tools
docker container for bitbucket pipelines

## How to use with bitbucket piplines

    - step:
        name: Mongodump
        image: meffulka/mongo-tools
        script:
          - mongodump ...
    - step:
        name: Mongorestore
        image: meffulka/mongo-tools
        script:
          - mongorestore ... <folder_with_dumps>
