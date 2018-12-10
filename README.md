# raxml-docker
Ubuntu 18.04 with RAxML 8.2.12 installed.

```bash
docker run -it --rm -v $(pwd):/in/ -w /in/ chrishah/raxml-docker:8.2.12 raxml
```

```bash
docker run -it --rm -v $(pwd):/in/ -w /in/ chrishah/raxml-docker:8.2.12 ProteinModelSelection.pl
```
