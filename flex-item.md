#flex-grow

```html
<!DOCTYPE html>
<html>
<head>
<style>
.flex-container {
  display: flex;
  align-items: stretch;
  background-color: #f1f1f1;
}

.flex-container > div {
  background-color: DodgerBlue;
  color: white;
  margin: 10px;
  text-align: center;
  line-height: 75px;
  font-size: 30px;
}
</style>
</head>
<body>

<h1>The flex-grow Property</h1>

<p>Make the third flex item grow eight times faster than the other flex items:</p>

<div class="flex-container">
  <div style="flex-grow: 1">1</div>
  <div style="flex-grow: 1">2</div>
  <div style="flex-grow: 8">3</div>
</div>

</body>
</html>

```
### Output
![image](https://user-images.githubusercontent.com/12442613/188301134-7094259e-2fe8-487a-bbd7-a9b48bfc14bf.png)

-------------------

# flex-shrink

```html

<!DOCTYPE html>
<html>
<head>
<style>
.flex-container {
  display: flex;
  background-color: #f1f1f1;
}

.flex-container>div {
  background-color: DodgerBlue;
  color: white;
  width: 100px;
  margin: 10px;
  text-align: center;
  line-height: 75px;
  font-size: 30px;
}
</style>
</head>
<body>

<h1>The flex-shrink Property</h1>

<p>Do not let the third flex item shrink as much as the other flex items:</p>

<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div style="flex-shrink: 0">3</div>
  <div>4</div>
  <div>5</div>
  <div>6</div>
  <div>7</div>
  <div>8</div>
  <div>9</div>
  <div>10</div>
</div>

</body>
</html>
```
![image](https://user-images.githubusercontent.com/12442613/188301177-d9597602-5524-414d-8d2c-ee6915cc0e4f.png)

---------------------------
# flex-basis

```html
<!DOCTYPE html>
<html>
<head>
<style>
.flex-container {
  display: flex;
  align-items: stretch;
  background-color: #f1f1f1;
}

.flex-container > div {
  background-color: DodgerBlue;
  color: white;
  width: 100px;
  margin: 10px;
  text-align: center;
  line-height: 75px;
  font-size: 30px;
}
</style>
</head>
<body>

<h1>The flex-basis Property</h1>

<p>Set the initial length of the third flex item to 200 pixels:</p>

<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div style="flex-basis:200px">3</div>
  <div>4</div>
</div>

</body>
</html>

```
![image](https://user-images.githubusercontent.com/12442613/188301216-0184ff11-5a11-46d3-a613-d7098d3d317b.png)


--------------

# The align-self Property

```html
<!DOCTYPE html>
<html>
<head>
<style>
.flex-container {
  display: flex;
  height: 200px;
  background-color: #f1f1f1;
}

.flex-container > div {
  background-color: DodgerBlue;
  color: white;
  width: 100px;
  margin: 10px;
  text-align: center;
  line-height: 75px;
  font-size: 30px;
}
</style>
</head>
<body>

<h1>The align-self Property</h1>

<p>The "align-self: flex-start;" aligns the selected flex item at the top of the container.</p>
<p>The "align-self: flex-end;" aligns the selected flex item at the bottom of the container.</p>

<div class="flex-container">
  <div>1</div>
  <div style="align-self: flex-start">2</div>
  <div style="align-self: flex-end">3</div>
  <div>4</div>
</div>

<p>The align-self property overrides the align-items property of the container.</p>

</body>
</html>

```
![image](https://user-images.githubusercontent.com/12442613/188301258-bbd58b56-1847-4845-9153-141309d3c71a.png)



