File Description
This directory contains 17 split-volume compressed files (.zip) that collectively store a large dataset or resource. These files are part of a multi-part archive and must all be downloaded to successfully extract the contents.

Prerequisites
Download ALL 17 files to the same folder
Ensure filenames remain unchanged (e.g., filename.z01, filename.z02... or filename.part1.rar, filename.part2.rar)
Install compression software:
Windows: WinRAR / 7-Zip
macOS: The Unarchiver / Terminal
Linux: unzip/unrar via terminal

Step-by-Step Guide
For Windows/macOS (GUI):
Place all 17 files in one folder
Right-click the FIRST file (usually .part1.rar or .zip.001)
Select "Extract Here" or "Extract to [folder name]"
The software will automatically combine volumes

For Linux/macOS (Terminal):
# For ZIP split files (e.g., filename.zip.001)
zip -s 0 filename.zip --out fullfile.zip && unzip fullfile.zip
# For RAR split files (e.g., filename.part1.rar)
unrar x filename.part1.rar
# For 7-Zip split files (e.g., filename.7z.001)
7z x filename.7z.001

Important Notes
Do NOT rename files - Original naming is critical
No missing parts - All 17 files must be present
File order matters - Parts must be numbered consecutively
Extraction time may be longer for large files

