applications:
- path: .
  memory: 512M
  instances: 1
  domain: mybluemix.net
  name: hackathon
  host: hackathon
  disk_quota: 1024M
  services:
  - availability-monitoring-auto
