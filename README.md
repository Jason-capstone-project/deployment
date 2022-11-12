# deployment

## install your server on the cloud and make sure you can connect it with ssh

```
ssh -i <key> <username>@<server ip or domain>
```

## on your computer make sure you have ssh key

if you don't have
copy the public key in your clipboard

## make sure you copy your public key to the root ssh folder

```
cd /root/.ssh/
nano authorized_keys
```