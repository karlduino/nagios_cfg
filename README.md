Config files for Nagios for network monitoring

config files stored in `/usr/local/nagios/etc/`

- `libexec/check_speedtest-cli.sh` - modified version of the speedtest check script, to find local server
- `libexec/run_speedtest.sh` - script to do test-run of check_speedtest-cli.sh

Test the configuration with

```shell
sudo /usr/local/nagios/bin/nagios -v /usr/local/nagios/etc/nagios.cfg
```
