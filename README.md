# DZNETeam

import os

# List of directories to create
directories = ['dataio', 'processing', 'analyze', 'tests', 'configuration', 'demodata']

# Loop through the list and create directories
for directory in directories:
    os.makedirs(directory, exist_ok=True)
