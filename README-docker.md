# Build (`Do this first!`)
    ```
    make build
    ```

# Run (recommended for easy-start)
```
./run.sh
```

# Stop Running
```
./stop.sh
``

# ISSUES
* React Native Error: ENOSPC: System limit for number of file watchers reached:
  Please run the following to solve the host limit:
```
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf
sudo sysctl -p
```

