# Docker image with Python and GDAL

Installs and compiles the latest version of GDAL.

Add following dependencies to requirements.txt:

```python
GDAL>=2.2.4
```

## Building container
```bash
# Pull latest image based on Debian Stretch and Python 3.6
docker pull thinmy/python-gdal:3.6-stretch

# Build without docker cache
docker build --no-cache thinmy/python-gdal:3.6-stretch
```

## Running container
```bash
docker run thinmy/python-gdal:3.6-stretch
```
