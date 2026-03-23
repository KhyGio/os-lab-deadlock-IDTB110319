# os-lab-deadlock-IDTB110319

## Checkpoint 1 — Loop devices mounted

![App Screenshot](img/checkpoint1.png)
The output of `df -h | grep loop` confirms that both virtual disk images (`vault_alpha.img` and `vault_beta.img`) are attached as loopback devices (`/dev/loop55` and `/dev/loop51`) and successfully mounted with an accessible  ext4 file system, proving the virtual drives are live and ready for use.
