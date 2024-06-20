# SRT to Audacity Labels Converter

This repository contains a Python script that converts SRT subtitle files into a format compatible with Audacity's label track. This tool is useful for audio and video editors who need to import subtitle timing data into Audacity for precise synchronization and editing of audio tracks.

## Features

- Converts SRT subtitle files to Audacity-compatible label files.
- Supports precise timing with six decimal places for start and end times.
- Easy to use with command-line arguments.

## Requirements

- Python 3.x

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/kyle95wm/srt-2-audacity.git
cd srt-2-audacity```


## Usage

To use the script, run it from the command line with the following syntax:

```python3 2audacity.py <inputfile.srt> <outputfile.txt>```

## Example

```python3 2audacity.py "AlRawabi School for Girls_S01E01_School Was My Happy Place.srt" "output-labels.txt"```

This command will read the SRT file AlRawabi School for Girls_S01E01_School Was My Happy Place.srt and generate an Audacity label file output-labels.txt.

## Primary Use Case

This script is designed for audio and video editors who use Audacity for their editing work. By converting SRT subtitle files into a format that Audacity can read, it allows editors to easily synchronize subtitles with their audio tracks, making it easier to ensure accurate timing and alignment.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request with your changes. Any contributions, whether they are bug fixes, new features, or improvements to documentation, are welcome.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
