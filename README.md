# Automatically test ads.txt with Github Actions

Specification: https://iabtechlab.com/ads-txt/

Other Validator: https://adstxt.guru/validator/


## What's this?

Test adds.txt(app-ads.txt) each time you push.

Just copy `.github/workflows/test.yml` and you're good to go!


## In case of error

Error fields and the number of rows are displayed.

```
Line 1159: ad-generation.jp,11164,DIREC-T,7f4ea9029ac04e53
invalid string: DIREC-T

Error: Process completed with exit code 255.
```
