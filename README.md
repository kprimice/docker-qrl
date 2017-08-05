[QRL]: https://theqrl.org
[github]: https://github.com/theQRL
[ircurl]: https://qr-ledger.slack.com

A QRL container

## Usage

```
docker create \
  --name docker-qrl \
  -v /etc/localtime:/etc/localtime:ro \
  -v </path/to/qrl/data>:/data \
  kprimice/docker-qrl
```

## Parameters

* `-v /etc/localtime` - synchronize time with host
* `-v /data` - wallet, chain and logs directory
