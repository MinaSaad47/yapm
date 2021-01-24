# Yet another password manager

simple posix shell password manager script that uses demu or rofi for selecting a password.


## Usage

### setup the global key (passowrd)
```bash
./yapm --setup
```

### Encrypt (add) a password to the vault
```bash
./yapm --encrypt
```

### Decrypt a password (copied to clipboard)
```bash
./yapm --decrypt
```


this script saves configuration files to $HOME/.config/yapm/ in order to save your hashed key.


