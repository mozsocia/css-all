# css for container


```html

<!DOCTYPE html>
<html>
<head>
<style>
.flex-container {
  display: flex;
   /*flex-direction: row;   by default  */  
  /* align-items: stretch;    by default  */
  /* justify-content: flex-start;    by default  */
  
  background-color: DodgerBlue;
  height: 300px;
  
}

.flex-container > div {
  background-color: #f1f1f1;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
}
</style>
</head>
<body>

<h1>Create a Flex Container</h1>

<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>  
</div>



</body>
</html>

```
### Output
![image](https://user-images.githubusercontent.com/12442613/188298434-2f559826-6a21-4260-b3ab-790dbfbe07fa.png)

-----------

```css
.flex-container {
  display: flex;
  background-color: DodgerBlue;
  height: 300px;
  align-items: center;
}
```
### Output
![image](https://user-images.githubusercontent.com/12442613/188298516-82ea4246-c593-4661-9360-d200ba7c7409.png)


---------------

```css
.flex-container {
  display: flex;
  background-color: DodgerBlue;
  height: 300px;
  justify-content: center;
}
```
### Output
![image](https://user-images.githubusercontent.com/12442613/188298562-2822487d-a958-4b0e-99f8-47412a0eddfe.png)





