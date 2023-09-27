# css-grid-repo

https://github.com/sait-wbdv/dailies-f23/blob/main/2023-09-27-gallaries/01-2up-starter/index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>2-up Starter</title>
  <link rel="stylesheet" href="css/main.css">
</head>
<body>
  <header>
    <img src="https://picsum.photos/id/380/500/500" alt="Some random photo">
    <h1>Check out my stuff!</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt enim animi velit, at illo nobis vel, magni, omnis eligendi eveniet necessitatibus. Veniam fuga distinctio debitis minima. Excepturi reprehenderit eius nobis.</p>
    <img src="https://picsum.photos/id/225/500/500" alt="Some random photo">
  </header>
</body>
</html>

header {
  display: grid;
  grid-template-columns: 1fr 1fr;
}

img {
  width: 100%;
}