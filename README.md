# MyEra-HTML-Blogs
Reference Repo for all blogs and guide to make new ones

## Blog Skeleton
While creating a new blog, the skeleton of the blog is as follows;

```
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>
<body class="container">

<!-- 	Body goes here... -->
<!-- Write your content here -->

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous">
</script>
</body>
</html>
```



## Adding Images
To add an image to blog, upload the image to Image feild of the blog, copy the link address of the image and use it as ```src``` of the image tag in html. 

## Styling
Bootstrap CDN is included in the skeleton. All bootstrap classes can be used. 

### Examples

- Header Image
```
<div style="text-align: center;">
	<img src="{{image_link}}" style="border-radius: 15px; margin-top: 2%; margin-bottom: 2.5%; width: 90%;">
</div>
```
- Blog Images
```
<div style="text-align: center;">
	<img src="{{image_link}}" style="border-radius: 15px; margin-top: 2.5%; margin-bottom: 5%; width: 50%;">
</div>
```
- Default Button
```
<a class="btn btn-primary">Get Started now! </a>
```
- Outlined Button
```
<a class="btn btn-outline-primary">Click here to register on MyEra </a>
```
