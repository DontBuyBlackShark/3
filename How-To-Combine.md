```py
# Download them
aria2c -x16 -s20 -ctrue https://github.com/DontBuyBlackShark/3/releases/download/FULLOTA-KLEN2011100CN00MQ3/20201113095044-klein-ota-signed_by_xiaomi_50fbd88a4e23e10d3f4cbb7e2d11add1.zip.001 &
aria2c -x16 -s20 -ctrue https://github.com/DontBuyBlackShark/3/releases/download/FULLOTA-KLEN2011100CN00MQ3/20201113095044-klein-ota-signed_by_xiaomi_50fbd88a4e23e10d3f4cbb7e2d11add1.zip.002 &

# When downloaded them, combine these.
cat FULLOTA-KLEN*MQ3*.zip.* > Combined.zip
```
