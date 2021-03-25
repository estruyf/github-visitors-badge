# GitHub Visitors Badge

Want to show how many visitors your profile/repository gets? With this simple visitors badge system, you can add it to your own profile page or repository.

<p align="center">
  <a href="#">
      <img src="http://estruyf-github.azurewebsites.net/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColor=%237B1E7A" />
   </a>
</p>

> **Info**: This service is currently running on Azure Functions.

## Parameters

The image API has the following parameters:

- **user** (required): Your username
- **repo**: The repository to start the visitor tracking.
- **label**: Label to show next to the counter. Default is "VISITORS".
- **labelColor**: Specify the color of the label (left).
- **countColor**: Specify the color of the counter (right).

## How to use

In order to use it in your projects, add the following to your README.md file:

```markdown
![](https://estruyf-github.azurewebsites.net/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColorcountColor&countColor=%237B1E7A)
```
