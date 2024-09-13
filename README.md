
# Anand Mehra Post Tool

## Overview

The Anand Mehra Post Tool is a Python script designed to automate posting comments on Facebook posts using cookies. It supports both manual and file-based input methods for cookies, post IDs, and comments. The tool features error handling, customizable delays, and support for random delay intervals between requests.

## Features

- **Manual and File-Based Input**: Choose between manually entering cookies, post IDs, and comments, or using input files.
- **Dynamic Comment Posting**: Post comments on Facebook posts with the ability to include custom names and messages.
- **Error Handling**: Handles errors gracefully and retries failed requests with randomized delays.
- **Internet Connectivity Check**: Ensures the script waits for a stable internet connection before proceeding.

## Requirements

- Python 3.x
- `requests`
- `pytz`

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/thehunter404devil/POST.git
   
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd POST
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Configure the Script**:
   - Replace `'YOUR_ACCESS_TOKEN_HERE'` in the script with your actual Facebook access token.

2. **Run the Script**:
   ```bash
   python PostTool.py
   ```

3. **Follow On-Screen Prompts**:
   - Choose between manual input or file-based input.
   - Provide necessary details as prompted.

## Input Files

- **Manual Input**: Enter cookies, post IDs, and comments manually.
- **File-Based Input**:
  - `cookies.txt`: List of cookies, one per line.
  - `post.txt`: List of post IDs, one per line.
  - `name.txt`: File containing the commenter's name.
  - `speed.txt`: File containing the delay in seconds.
  - `file.txt`: File containing comments, one per line.

## Example

To run the script with manual input:
1. Choose `1` for manual input.
2. Enter the number of cookies, post IDs, and other details as prompted.

To run the script with file-based input:
1. Choose `2` for file-based input.
2. Provide the paths to the required files when prompted.

## Notes

- Ensure you have an active internet connection.
- The script handles cookies and posts based on the Facebook Graph API, so it requires valid access tokens and cookies.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For issues or questions, please contact [Anand Mehra](mailto: mm9736090@gmail.com)
whatsp:+917643890954.
