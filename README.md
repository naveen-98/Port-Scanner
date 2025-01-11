
# Port Scanner

This project is a simple **Port Scanner** written in Java. It scans a given IP address for open ports within the range of 1 to 65535. The scanner uses multi-threading to efficiently probe ports and provides a quick report of open ports.

## Features

- Scans all ports (1-65535) on a specified IP address.
- Multi-threaded for faster execution.
- Customizable timeout for port scans.

## Requirements

- Java Development Kit (JDK) 8 or higher.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/naveen-98/Port-Scanner.git

2. Navigate to the project directory:
   ```bash
   cd Port-Scanner

3. Compile the Java code:
   ```bash
   javac PortScanner.java


# Usage

1. Run the program:
    ```bash
   java PortScanner

2. Input the IP address you want to scan when prompted.

3. The program will output the open ports found on the given IP address.

# Example

Please input the ip address you would like to scan for open ports: 192.168.1.1

22

80

443

There are 3 open ports on host 192.168.1.1 (probed with a timeout of 200ms)

## Demo

Check out the demo video to see the port scanner in action.

https://youtu.be/5VKJV_tnz_k?si=ipp9TXY91Ry5Tc_b

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Author

    N4viya98
