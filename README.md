# Fluree

Fluree is an immutable graph database that, beyond performing typical modern database functions, emphasizes security, trust, provenance, privacy, and interoperability
## Install latest version of java 
it can also be created using docker and homebrew

```bash
sudo apt install openjdk-11-jre-headless 
```

## Install flurry

```bash
https://fluree-releases-public.s3.amazonaws.com/fluree-[MAJOR VERSION].[MINOR VERSION]-latest.zip
```

## export files and navigate to the folder to launch fluree

```bash
./fluree_start.sh
```
### creation of a ledger
```bash
my/ledger
```
### Adding a collection
``` fluree
[
  {
    "_id": "_collection",
    "name": "person"
  },
  {
    "_id": "_collection",
    "name": "chat"
  },
  {
    "_id": "_collection",
    "name": "comment"
  },
  {
    "_id": "_collection",
    "name": "artist"
  },
  {
    "_id": "_collection",
    "name": "movie"
  }
]
```
