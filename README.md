# Reference

- https://github.com/zeroclaw-labs/zeroclaw/blob/master/docs/book/src/setup/container.md
- Setup Hermes:
```
sudo docker run -it --rm -e HERMES_UID=1000 -e HERMES_GID=1000 -v ./data/hermes:/opt/data nousresearch/hermes-agent setup
```