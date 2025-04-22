1. Export Required Variables
``` console
export ABBR=<Your Short Abbreviation, no longer than 4 characters>
```
2. Copy pipeline to with your abbreviation
``` console
cp cf-shared-ci-cd.yaml $ABBR-cf-shared-ci-cd.yaml
```
3. Create branch based on your abbreviation. 
``` console
git checkout -b $ABBR
```
4. Push your branch to GitHub.
``` console
git push --set-upstream origin $ABBR
```
5. Follow Pipeline Lab Exercise for additional instructions.