# Debugging Bash Script

## Use Bash Debug Mode
Run the script with debug tracing
```bash
   bash -x bash-scrip.sh
```

## Inside srcipt file
```bash
   if [ $? - ne 0 ]; then
        echo "Error"
   fi
```
