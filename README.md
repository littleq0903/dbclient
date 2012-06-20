DBClient
========

Command-line tool for Dropbox accessing


## Installation

1. `git clone git@github.com:littleq0903/dbclient.git`
2. `cd dbclient`
3. `sudo pip install -r requirements.txt`
4. Move `dbclient` to any directory which is under your `PATH`. (e.g. `sudo cp dbclient /usr/local/bin`)

## Usage

* `dbclient ls [<remote-path>]`: listing files
* `dbclient cd [<remote-path>]`: change the current working remote directory.
* `dbclient pwd`: show current working directory
* `dbclient get <remote-path> [<local-path>]`: download a file
* `dbclient put <local-path> [<remote-path>]`: upload a file
* `dbclient share <remote-path>`: get a public link for a file
* `dbclient info`: show account info
* `dbclient reset`: reset the authentication status

## Contribution

Contribution and advises are welcome.

* Author: LittleQ
* E-Mail: littleq0903@gmail.com