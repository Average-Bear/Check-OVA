Scan-OVAHash

This script will check a decompressed OVA/OVF for file integrity.

This script can be useful to verify files before attempting to import into your virtual environment. It's particularly useful when many vmdk files are present.

This script will parse the included manifest file in the path provided and use these stored hashes to compare against newly calculated ones. A mismatch indicates a corrupt/changed file. Missing files will also be flagged as failures.
