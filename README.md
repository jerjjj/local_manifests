# the source code from mt6768Team,I only revise some code

## 12

```bash
# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/jerjjj/local_manifests/main/twelve.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```

## 13

```bash
# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/jerjjj/local_manifests/main/thirteen.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```