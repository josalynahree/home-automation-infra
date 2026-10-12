# Docker Compose Notes

## Services
- Home Assistant: `ha.example.com`
- MQTT broker: `mqtt.example.com`
- ESP device endpoint: `esp.example.com`

## Deployment
- Project platform: Railway
- Repository: home-automation-infra
- Container configuration: Docker Compose
- Configure the actual domain names and DNS targets before deployment.
- Store passwords and tokens in environment variables or platform secrets.
- Do not commit credentials to GitHub.

## Networking
- Configure DNS records with the domain's DNS provider.
- Verify that each hostname resolves to its intended target.
- Configure TLS and service ports according to each service's requirements.

## Important
These are planning notes. Confirm that each service is supported by the chosen deployment platform and that the actual deployment configuration matches these notes.
