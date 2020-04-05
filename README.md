# Monitor your go-eCharger with Telegraf

This is a set of tools for monitoring you Go-eCharger with Telegraf. It uses the MQTT functionality for gathering data, therefore you need an MQTT broker.

![Grafana screenshot](support/go-echarger_grafana.png)

## Installation

Edit `telegraf.d/go-echarger.conf` to use your MQTT server. The telegraf config file is installed to `/etc/telegraf/telegraf.d/`.
