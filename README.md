# benchmark

## Installation Steps

```sh
# Download HAR file and move to ./har
mv ~/**/sandbox.shikshaplatform.io.har ./har/

# Create a virtual env and activate it
python3 -m venv venv
source venv/bin/activate

# Install HAR to locust converter
pip install har-transformer

# Create locust file from all HAR files
transformer ./har/ >locustfile.py

# Restart docker to mount the new locust file.
docker-compose up
```

## Status 

| **Module** | **Status** |
| --- | --- |
| Role | Done |
| Worksheet | Done |
| Attendance | Done |
| Group | Done |
| School | Done |
| Config | Done |
| Like | Done |
| Comment | Done |
| User | Done |
| Template | Done |

