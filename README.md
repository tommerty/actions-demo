# Prerequisites
 - [Python3]([https://www.python.org/downloads/](https://www.python.org/downloads/))
	 - Also enure to run
	 - `python3 -m pip install requests`

## Installation
1. Download and extract the `wpe_merge.zip` 
2. `sudo mv ~/Downloads/wpe_merge/wpe_merge.sh /usr/local/bin/wpe_merge`
3. `sudo mv ~/Downloads/wpe_merge/wpe_merge.py /usr/local/bin/`
4. `chmod +x /usr/local/bin/wpe_merge`
5. `chmod +x /usr/local/bin/wpe_merge.py`

## Usage
Run `wpe_merge [file/path/to/input_file.csv] [file/path/to/output.csv]`, replacing the paths to what's relative.

Example usage: `wpe_merge /Users/username/Downloads/input.csv /Users/username/Downloads/output.csv` = will generate the `output.csv` file with the added columns.