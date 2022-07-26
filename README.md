# Check out the new website to create your own visitor badges


[visitorbadge.io](https://www.visitorbadge.io/)


# GitHub Visitors Badge

Want to show how many visitors your profile/repository gets? With this simple visitors badge system, you can add it to your own profile page or repository.

<p align="center">
  <a href="#">
      <img src="https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColor=%237B1E7A" />
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
![](https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColor=%237B1E7A)
```

![](https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColor=%237B1E7A)

You can customize left text (default is "VISITORS"):

```markdown
![](https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColor=%237B1E7A&label=helloVisitors)
```

![](https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColor=%237B1E7A&label=helloVisitors)

Feel free to add a space between words in left text:

```markdown
![](https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColor=%237B1E7A&label=thanks%20for%20visiting)
```

![](https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColor=%237B1E7A&label=thanks%20for%20visiting)

Change badge colors:

```markdown
![](https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&labelColor=%23313131&countColor=%23FFDD33&label=hi%20friends)
```

![](https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&labelColor=%23313131&countColor=%23FFDD33&label=hi%20friends)
