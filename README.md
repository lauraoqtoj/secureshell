# SecureShell

SecureShell is a Python program designed to implement additional security measures for remote access protocols on Windows systems. The goal is to prevent unauthorized access by managing the Remote Desktop Services and encrypting sensitive information.

## Features

- **Encryption**: Uses symmetric encryption to secure sensitive data.
- **Service Management**: Enables and disables Remote Desktop Services as needed.
- **Logging**: Logs activities for auditing and troubleshooting.

## Prerequisites

- Python 3.x
- `cryptography` library: Install using `pip install cryptography`

## Usage

1. **Generate Encryption Key**: The program automatically generates an encryption key if it does not exist.
2. **Encrypt/Decrypt Data**: SecureShell can encrypt and decrypt data using the generated key.
3. **Manage Remote Desktop Services**: The script checks the status of the Remote Desktop Services and can disable them to prevent unauthorized access.

## How to Run

1. Clone the repository or download the `secureshell.py` file.
2. Ensure you have Python and the required library installed.
3. Run the script using the command:
   ```bash
   python secureshell.py
   ```

## Security Considerations

- Ensure the `encryption.key` file is stored securely and only accessible by authorized users.
- Regularly update and review the security measures implemented by SecureShell.

## Logs

All activities and events are logged in `secureshell.log` for monitoring and troubleshooting purposes.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any bugs or suggestions.

## License

This project is licensed under the MIT License.