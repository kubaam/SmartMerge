# Merge and Remove Duplicates in Text Files

This is a simple command-line tool for merging multiple text files and removing duplicate lines. It's written in Rust and uses the Rayon library for multi-threading.

## Features

- Merges multiple text files into one.
- Removes duplicate lines from the merged file.
- Supports multi-threading for faster performance.
- Shows progress bars for every operation, with estimated remaining time.
- Removes empty lines from the input files.
- Works on any platform where Rust is supported.

## Usage

To run the tool, navigate to the directory containing the text files you want to merge, then run the following command:

```$ merge_remove_duplicates```


By default, the tool will merge all the .txt files in the current directory. You can specify a different directory as the first argument:


```$ merge_remove_duplicates /path/to/text/files```


The tool will merge all the .txt files in the specified directory.

## Installation

To install the tool, you need to have Rust installed on your system. You can install Rust by following the instructions on the [official Rust website](https://www.rust-lang.org/tools/install).

Once you have Rust installed, you can install the tool using Cargo, Rust's package manager:

```$ cargo install merge_remove_duplicates```


This will download the tool from the [crates.io](https://crates.io/crates/merge_remove_duplicates) repository and install it on your system.

## License

This tool is released under the [MIT License](https://opensource.org/licenses/MIT).

## Contributing

If you find a bug or have a suggestion for a new feature, please open an issue on the [GitHub repository](https://github.com/yourusername/merge_remove_duplicates). Pull requests are also welcome!
