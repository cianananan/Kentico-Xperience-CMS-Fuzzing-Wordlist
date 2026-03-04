# Kentico-Xperience-CMS-Fuzzing-Wordlist
A wordlist for fuzzing Kentico Xperience during penetration tests or CTFs.
For authorised security testing only, please ensure you have permission before fuzzing or attacking a target.

## Usage
Use with FFuF for faster fuzzing (u fool!).
`ffuf -c -w kentico-wordlist.txt -u 'https://target.com/FUZZ' -mc 200,301,302,403`

Happy fuzzing!
