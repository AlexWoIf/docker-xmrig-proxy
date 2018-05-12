# Dockerized XMRig Proxy

Based on original xmrig/xmrig-proxy v1.6.2

### Options
```
  -b, --bind=ADDR          bind to specified address, example "0.0.0.0:3333"
  -a, --algo=ALGO          cryptonight (default) or cryptonight-lite
  -m, --mode=MODE          proxy mode, nicehash (default) or simple
  -o, --url=URL            URL of mining server
  -O, --userpass=U:P       username:password pair for mining server
  -u, --user=USERNAME      username for mining server
  -p, --pass=PASSWORD      password for mining server
  -r, --retries=N          number of times to retry before switch to backup server (default: 1)
  -R, --retry-pause=N      time to pause between retries (default: 1 second)
      --custom-diff=N      override pool diff
      --reuse-timeout=N    timeout in seconds for reuse pool connections in simple mode
      --verbose            verbose output
      --user-agent=AGENT   set custom user-agent string for pool
      --no-color           disable colored output
      --no-workers         disable per worker statistics
      --variant            algorithm PoW variant
      --donate-level=N     donate level, default 2%
  -B, --background         run the miner in the background
  -c, --config=FILE        load a JSON-format configuration file
      --no-watch           disable configuration file watching
  -l, --log-file=FILE      log all output to a file
  -S, --syslog             use system log for output messages
  -A  --access-log-file=N  log all workers access to a file
      --api-port=N         port for the miner API
      --api-access-token=T use Bearer access token for API
      --api-worker-id=ID   custom worker-id for API
      --api-no-ipv6        disable IPv6 support for API
      --api-no-restricted  enable full remote access (only if API token set)
  -h, --help               display this help and exit
  -V, --version            output version information and exit
```

