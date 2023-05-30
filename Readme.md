# Opensearch

## 0. set sysctl
```
# vim /etc/sysctl.conf
vm.max_map_count=262144

# sysctl -p

OR
# sysctl -w vm.max_map_count=262144
```

## 1. git clone project
```
# git clone https://github.com/thanachaiTP/opensearch.git
# cd opensearch
```

## 2. create directory 
```
# mkdir -p data && chown -R 1000:1000 data
```

## 3. deploy opensearch
```
# docker-compose up -d
```

