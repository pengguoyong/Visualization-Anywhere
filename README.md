# Visualization-Anywhere
Network Operations Center Dashboard
I am assuming you have TIG (Telegraf/Influx/Grafana) setup for general dashboard purposes. This is really simplle to setup and there are lots of blogs on this.

Setup The Custom Script
The script is going to call DNAC API via the newly released SDK.

I am going to assume a directory /opt/telegraf. If you want to install elsewhere you need to change the paths in the custom.conf file.

First (optional) step, create a vitualenv. This makes it less likely to clash with other python libraries in future. Once the virtualenv is created, need to activate it.

python3 -mvenv env3
source env3/bin/activate
