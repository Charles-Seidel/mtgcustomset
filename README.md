# mtgcustomset
Custom MTG set

When developing please add these lines to your `.git/hooks/pre-commit` file so we can track the diff to individual cards

```
rm -rf "Nature vs Future"
unzip "Nature vs Future.mse-set" -d "Nature vs Future"
git add "Nature vs Future"```
