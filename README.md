# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/jerjjj/local_manifests/main/twelve.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```