# apt-get Packages

## Clipboard Copy/Paste

```bash
sudo apt-get install xsel -y; \
echo -e "alias pbcopy='xsel --input --clipboard'\nalias pbpaste='xsel --output --clipboard'" > .bashrc;
```
