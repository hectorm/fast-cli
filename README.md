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
fast
```

### Save output to a CSV file
```sh
fast > results.csv
```
