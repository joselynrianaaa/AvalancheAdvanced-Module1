## Installation


### Instructions

To Download latest release :

```sh
curl -sSfL https://raw.githubusercontent.com/ava-labs/avalanche-cli/main/scripts/install.sh | sh -s
```

File will be installed into the ~bin directory

To add the binary to your path, run

```sh
export PATH=~/bin:$PATH
```

To add it to your path permanently, add an export command to your shell initialization script (ex: .bashrc).


## Quickstart

Launch you custom subnet specifying the subnet name

```bash
avalanche subnet create <subnetName>
avalanche subnet deploy <subnetName>
```

Shut down your local deployment with:

```bash
avalanche network stop
```
## Authors

Joselyn Riana joselynriana@gmail.com

## License

This project is licensed under the MIT License
