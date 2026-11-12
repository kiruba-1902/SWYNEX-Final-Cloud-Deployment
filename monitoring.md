# CloudTask – Monitoring and Cost Awareness

## 1. Introduction

Monitoring helps ensure that the CloudTask website is accessible and that deployments are working correctly.

This document describes the monitoring checks and cost-awareness practices used for the project.

## 2. Website Availability

- Open the live website periodically.
- Confirm that the homepage loads successfully.
- Check that the task interface responds correctly.
- Verify that the website is accessible through HTTPS.

**Live URL:**

https://sensational-cucurucho-1bf736.netlify.app/

## 3. Deployment Monitoring

Netlify provides deployment status and logs.

Monitoring activities:

- Check the production deployment status.
- Confirm that the latest deployment is Published.
- Review deployment logs for errors.
- Verify the connected GitHub repository and main branch.
- Test the website after a new deployment.

## 4. Application Testing

Perform basic manual testing:

- Open the website in a browser.
- Test task creation and interaction.
- Check task completion functionality.
- Refresh the page and check expected behaviour.
- Inspect browser developer tools for errors.

## 5. Cost Awareness

Cost-management practices:

- Review Netlify plan limits and usage.
- Monitor bandwidth and build usage where available.
- Optimize images and other static assets.
- Avoid unnecessary paid services.
- Remove unused resources.
- Review hosting usage periodically.

## 6. Security Practices

- Use HTTPS.
- Do not commit passwords or API keys.
- Enable multi-factor authentication.
- Use appropriate repository permissions.
- Avoid storing sensitive personal information.

## 7. Monitoring Limitations

- The application is a static frontend.
- There is no backend server or database.
- Netlify deployment logs are not backend application logs.
- Advanced uptime alerts are not considered active unless separately configured and tested.

## 8. Monitoring Record Template

| Date | Check | Result | Notes |
|---|---|---|---|
| YYYY-MM-DD | Website availability | Pass/Fail | Add observation |
| YYYY-MM-DD | Deployment status | Pass/Fail | Add observation |
| YYYY-MM-DD | Application functionality | Pass/Fail | Add observation |
| YYYY-MM-DD | Hosting usage review | Reviewed | Add observation |

## 9. Conclusion

Monitoring and cost awareness help maintain a reliable and efficient cloud-hosted website. Regular deployment checks, manual testing, usage reviews, and security practices support the successful operation of CloudTask.
