[![Node.js CI](https://github.com/nghiant/connect-air-frontend//actions/workflows/node.js.yml/badge.svg)](https://github.com/nghiant/connect-air-frontend//actions/workflows/node.js.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=nurikk_/nghiant/connect-air-frontend/&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=nurikk_/nghiant/connect-air-frontend/)
[![codebeat badge](https://codebeat.co/badges/5ca1254f-569b-4ec0-99fa-fe6f0fa2896b)](https://codebeat.co/projects/github-com-nurikk-/nghiant/connect-air-frontend/-dev)

# Screenshots

![](images/screenshot_home.png)
![](images/screenshot_map.png)

# Translation

You miss a translation? You want to help? You can contribute new languages and improvements via the external website [poeditor.com](https://poeditor.com/join/project?hash=Az88waAhPd).

# Develop

Install dependencies

```bash
pnpm install
````

Develop using mock data

```bash
npm run start
open http://localhost:3030/
````

Develop using your z2m instance

```bash
Z2M_API_URI="ws://192.168.1.200:8080" npm run start
open http://localhost:3030/
```

# Tests

```bash
npm run test:unit
```

# Build

```bash
npm install
npm run build //compiled files at ./dist
```

# Sponsors

[JetHome](https://jethome.ru/)


