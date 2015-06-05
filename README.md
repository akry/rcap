# RCAP

Capture packets from devices.

# Install

```
# bundle install --path vendor/bundle
```

# Help

```
# bundle exec bin/pcap -h
Usage: pcap [options]
        --tap=VALUE                  tap device name
        --ip=VALUE                   ip address
        --inst=VALUE                 instance name
        --server=VALUE               unity server ip
        --port=VALUE                 unity server port
```

# Usage

```
# bundle exec ./bin/pcap --tap=xxxxxxx --ip=10.0.1.10 --inst=lb-local --server=127.0.0.1 --port=20000
```
