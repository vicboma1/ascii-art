# Ascii-art 


Command
```
SEED=$(curl -s https://api.github.com/repos/vicboma1/ascii-art/git/trees/main | grep path | wc -l)
curl -s https://raw.githubusercontent.com/vicboma1/ascii-art/main/$(( ( $RANDOM % ${SEED} )  ))
````

