# Q1

Bash command to run elasticsearch:
```bash
docker run -it \
    --rm \
    --name elasticsearch \
    -m 4GB \
    -p 9200:9200 \
    -p 9300:9300 \
    -e "discovery.type=single-node" \
    -e "xpack.security.enabled=false" \
    docker.elastic.co/elasticsearch/elasticsearch:8.17.6
```

The build hash is dbcbbbd0bc4924cfeb28929dc05d82d662c527b7.


# Q2

index.


# Q3

See code in `Q2-6.ipynb`. The `response['hits']['hits']` shows 44.51 for the `_score` field.

# Q4

See code in `Q2-6.ipynb`. The third one shows "You can copy files from your local machine into a Docker container.."

# Q5

See code in `Q2-6.ipynb`. `len(prompt)` shows 1620.

# Q6

See code in `Q2-6.ipynb`. `len(encoding.encode(prompt))` shows 353.



