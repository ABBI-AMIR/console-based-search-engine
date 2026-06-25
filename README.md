version https://git-lfs.github.com/spec/v1
oid sha256:ca517d1dab2d39ee453c18a32fbb4bd482cbf1cbd6fc0c79186f7a7d3cbb8c77
size 72



A lightweight command-line search tool written in C that queries the Google Custom Search JSON API and stores your search history locally.


Features


Search the web directly from your terminal using Google's Custom Search API
Saves search history to search_history.txt and search_engine_history.json
Task tracking via tasks.json
Built with libcurl for HTTP requests and zlib for compression support
Prebuilt Windows binary included (main.exe)








File Structure

├── main.c                      # Main source file
├── main.exe                    # Prebuilt Windows binary
├── libcurl.dll                 # cURL shared library
├── zlib1.dll                   # zlib shared library
├── libcurl.pdb / zlib.pdb      # Debug symbols
├── google_custume_API_key.txt  # API key (keep private!)
├── search_history.txt          # Plain-text log of past searches
├── search_engine_history.json  # JSON log of search results/history
├── tasks.json                  # Task tracking data
├── mk-ca-bundle.pl             # Script to generate CA certificate bundle for curl
└── .vscode/
    └── c_cpp_properties.json   # VS Code C/C++ config


    
