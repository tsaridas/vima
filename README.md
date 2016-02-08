# vima : encrypt/decrypt yaml files with gpg
Tool to be used in order to encrypt yaml files with gpg.
It opens a yaml file in vim decrypted and encrypts it with the recepient when user exists vim.

# Purpose
It was created in order to encrypt saltstack pillar files that have a specific key and commit them to a repository using vim.

# Requires/Imports
yaml
pyaml
gnupg
tempfile
subprocess
os
sys
filecmp
copy
