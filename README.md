# tarballs

taking tarballs up the snooter

```sh
# required environment variables
$ export tarballs_iv=$128_bit_secret
$ export tarballs_key=$256_bit_secret

# generate a pathword
$ tarballs encrypt "chee/application"

# decrypt a pathword
$ tarballs decrypt "1626461d0451162y2u1c1x686u553316"

# start server
$ tarballs serve --extract-root /www/snoot.club/snoots --port 55433
```
