# fast-cli

Test your latency, download speed and upload speed using [fast.com](https://fast.com).

## Installation

```sh
sudo curl -o '/usr/local/bin/fast' 'https://raw.githubusercontent.com/hectorm/fast-cli/master/fast'
sudo chown root:root /usr/local/bin/fast
sudo chmod 755 /usr/local/bin/fast
```

## Usage

### Standard usage
```sh
$ fast
Latency (min/avg/max): 10.27/10.79/11.81 ms
Download speed (min/avg/max): 99.25/104.21/110.38 Mbps
Upload speed (min/avg/max): 12.17/12.21/12.23 Mbps
```

### Save output to a CSV file
```sh
$ fast > speedtest.csv
$ cat speedtest.csv
latency,10.27,10.79,11.81
download,99.25,104.21,110.38
upload,12.17,12.21,12.23
```
