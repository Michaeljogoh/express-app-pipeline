## express app

Access with browser http://localhost:8080

### Deployment pipeline

- GitHub Actions workflow: `.github/workflows/release-nodejs-app.yml`
- Local deployment with Watchtower: `docker-compose.yaml`
- Copy `.env.example` to `.env` and set your Docker Hub username before running compose.
