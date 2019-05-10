# Flume study
source = netcat
sink = logger
channel = memory

## reference
- https://flume.apache.org/FlumeUserGuide.html

## flume command

```
flume-ng agent --conf /etc/flume-ng/conf --conf-file=netcat.conf --name agent2 -Dflume.root.logger=INFO,console
```
