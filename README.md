# Merge and Remove Duplicates from Text Files
This Rust project merges multiple text files in a directory and removes any duplicate and empty lines from the resulting file. It's designed to handle large files efficiently using multithreading and provides progress bars for each operation, giving a real-time estimate of the remaining time.

Features
Merges all .txt files in the specified directory (defaults to the script's directory)
Removes duplicate lines and empty lines
Utilizes multithreading for better performance on large files
Provides progress bars for file processing and writing the output file
Displays the estimated remaining time for each operation
Usage
Install Rust if you haven't already.
Clone this repository:
git clone https://github.com/your_username/merge_remove_duplicates.git
Change to the project directory:
cd merge_remove_duplicates
uild the project:
cargo build --release
./target/release/merge_remove_duplicates /path/to/your/text/files

The merged and deduplicated file will be created in the same directory as the input files, with the name merged_deduped.txt.

Contributing
Contributions are welcome! Please feel free to submit a pull request or create an issue for any enhancements or bug fixes.

License
This project is licensed under the MIT License.
