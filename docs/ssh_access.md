# SSH Access

Being able to SSH into a machine is useful to flash firmware, modify files from the terminal, and download and run scripts.

## Usage

Use a command line interface, like Windows Terminal or [Tabby](tabby.sh), to SSH into your printer.

```bash
ssh user@your_ip_address
```

There are two user and password combos as of the 01.01.02.01 firmware update. This update and all after have the option of both users, while 1.1.1 and below only have `mks`.

|User|Password|
|---|---|
|mks|makerbase|
|qidi|qiditech|
