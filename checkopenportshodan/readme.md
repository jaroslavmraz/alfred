# ShodanQuery Alfred Workflow

## Overview

The ShodanQuery Alfred Workflow integrates the Shodan Internet Database with Alfred, enabling efficient querying of internet-connected devices directly from the macOS desktop environment. This tool is designed for professionals in cybersecurity, network administration, and technology research, facilitating rapid access to device information, security vulnerabilities, and network configurations.

![screanshoot](https://github.com/jaroslavmraz/alfred/blob/main/checkopenportshodan/screanshot.png)

## iOS version

[V1](https://www.icloud.com/shortcuts/c5ba75bd83df4537bc6a64e305826614)

## Features

- **Direct Query Execution**: Perform searches on the Shodan database using Alfred's input interface for both general overviews and specific device information.
- **Detailed Information Retrieval**: Access detailed data on IP addresses, including vulnerabilities, open ports, associated hostnames, and device configurations.
- **Efficient Workflow Integration**: Seamlessly fits into the user's workflow, leveraging Alfred's capabilities to enhance productivity and data accessibility.

## Installation

1. Ensure that Alfred 4 with Powerpack is installed on your macOS.
2. Clone this repository or download the workflow file.
3. Double-click the workflow file to import it into Alfred.
4. Dependencies such as `curl` and `jq` must be installed on your system for the workflow to function correctly. They can typically be installed via Homebrew with `brew install curl jq`.

## Usage

Invoke the workflow within Alfred using the designated keyword followed by your query. For specific IP address queries, append the IP address after the keyword. The workflow processes the input and displays the results directly within Alfred's interface.

## Prerequisites

- Alfred 4 with Powerpack license.
- `curl` and `jq` installed on macOS.

## Contribution

Contributions are welcome and greatly appreciated. Please fork the repository and submit pull requests with your enhancements. For bugs, feature requests, or additional documentation, open an issue in the repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Thanks to the Shodan team for providing the extensive database and API that facilitate this workflow.
