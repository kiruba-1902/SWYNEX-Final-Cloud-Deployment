# CloudTask – Cloud Architecture

## 1. Architecture Overview

CloudTask uses a static web application architecture. The frontend is developed using HTML, CSS, and JavaScript and hosted on Netlify.

GitHub stores the source code and is connected to Netlify for deployment.

## 2. Architecture Diagram

```text
        Developer
            |
            v
       GitHub Repo
            |
            v
     Netlify Build
            |
            v
      Netlify CDN
            |
            v
       End User
            |
            v
      Web Browser
            |
            v
       CloudTask
    HTML / CSS / JS
```

## 3. Main Components

### GitHub
- Stores application source code.
- Maintains version history.
- Provides the source repository for deployment.

### Netlify
- Hosts the static website.
- Connects to the GitHub repository.
- Publishes production deployments.
- Provides deployment logs and status information.

### Web Browser
- Loads the deployed website.
- Runs HTML, CSS, and JavaScript.
- Handles user interactions.

## 4. Data Flow

1. Developer pushes application code to GitHub.
2. Netlify retrieves the connected repository.
3. Netlify builds and publishes the website.
4. Users access the website through its public URL.
5. The browser renders the frontend application.

## 5. Architecture Benefits

- Simple deployment process.
- Easy source code management.
- Static hosting reduces infrastructure complexity.
- HTTPS support through Netlify.
- Deployment history and logs are available.

## 6. Architecture Limitations

- No dedicated backend server.
- No centralized database.
- Browser storage is specific to the user's browser.
- Advanced server-side monitoring is not applicable to this static application.
