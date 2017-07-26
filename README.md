# ELK Stack Lab

## What is this?

**ELK** stands for:

- **E**lasticsearch: The one that keeps
- **L**ogstash: The one that guides
- **K**ibana: The one that shows

## What I Need to Use?

Before trying to use this lab, make sure you...:

- Have the `git` command/package installed
- Have a functional `docker` environment
- Have the `docker-compose` command/package installed

## How Do I Use It?

Well...

![alt text](https://media.tenor.com/images/9112ee31c173e0074d97d36afde8dca0/tenor.gif "Well... obviously")

You need to:
1. Download this repository (`git clone https://github.com/fewbits/elk-lab.git`
1. Enter the **elk-lab** directory (`cd elk-lab`)
1. Review and, if needed, change the **docker-compose.yml** file to reflect to your needs (`vim docker-compose.yml`)
1. Run the lab (`docker-compose up -d`)

## What to Consider in *Production*?

When using **ELK** in *Production*, there are things that must be considered (remember, this is just a lab!):

### Elasticsearch

- Value of `vm.max_map_count` (please refer to https://hub.docker.com/_/elasticsearch/)

### Logstash

- N/A yet

### Kibana

- N/A yet
