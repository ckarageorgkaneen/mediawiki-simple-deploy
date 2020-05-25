Create volumes
-
```bash
mkdir database images
```

Deploy stack
-
```bash
docker stack deploy -c docker-stack.yml mediawiki
```

Setup mediawiki
-
```
1. Go to localhost:8080
2. Follow setup guide
3. Download LocalSettings.php to current directory
4. Uncomment respective line in docker-stack.yml
5. Redeploy stack to update mediawiki service
```
