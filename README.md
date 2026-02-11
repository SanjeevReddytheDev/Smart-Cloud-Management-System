
# Smart Cloud Management System (Mini)

## Features
- VM Provisioning Simulation
- Cost Monitoring
- Policy Enforcement (Max 5 VMs)
- Dashboard Interface

## Run Locally
pip install -r requirements.txt
python app/app.py

## Run with Docker
docker build -t scms-mini .
docker run -p 5000:5000 scms-mini
