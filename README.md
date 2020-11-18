# colabhash

#### Inspired by the excellent colabcat project by someshkar

This project aims to be faster at deploying hashcat on Google Colab<br>
by directly downloading the compiled binaries

<a href="https://colab.research.google.com/github/threadexio/colabhash/blob/main/colabhash.ipynb">Open in Colab</a>

# How to use:

### 1. Get a copy of the script on Google Colab

**NOTE:** If this is your first time running the script, run the first code cell<br>
      or create the folders `colabhash`, `colabhash/hashes/` and `colabhash/wordlists/` manually in the root of your Google Drive

### 2. Change the variables in the 3rd code cell

Remember to change:

`mode` to the mode of your hash<br>
(see https://hashcat.net/wiki/doku.php?id=example_hashes for more details)

`hash` to your hash or create a file in your `colabhash/hashes/` folder with your hashes and change `hash` to `your_hash_file.txt`

`wordlist` to your wordlist in `colabhash/wordlists/` (only use the file name, not the path)

### 2.1 Change the version of hashcat (Optional)

Change the variable `hashcat_version` to the version of hashcat you wish to use<br>
(see https://github.com/hashcat/hashcat/releases for available versions)

### 3. Run the 3rd code cell

And happy cracking!
