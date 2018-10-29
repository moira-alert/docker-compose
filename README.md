# Moira docker-compose

If you're new here, better check out our main [README](https://github.com/moira-alert/moira/blob/master/README.md).

## Installation

Docker Compose is the easiest way to try:

```
git clone https://github.com/moira-alert/docker-compose.git
cd docker-compose
docker-compose pull
docker-compose up
```

Feed data in Graphite format to `localhost:2003`:

```
echo "local.random.diceroll 4 `date +%s`" | nc localhost 2003
```

Configure triggers at `localhost:8080` using your browser.

Other installation methods are available, see [documentation](https://moira.readthedocs.io/en/latest/installation/index.html).

## Contact us

If you have any questions, you can ask us on [Telegram](https://t.me/moira_alert).
