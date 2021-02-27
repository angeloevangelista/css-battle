# Target #003 - Push Button

## Objective

<div align="center">

![Target #003 - Push Button](./.github/images/003.png)

</div>

## Code

```html
<div class="main">
  <div>
    <div></div>
  </div>
</div>
<style>
  body {
    display: flex;
    background: #6592CF;
  }

  .main {
    position: relative;
	  display: flex;
    margin: auto;
    width: 300px;
    height: 150px;
    background: #243D83;
  }

  .main > div {
    display: flex;
    position: absolute;
    width: 150px;
    height: 150px;
    border: solid 50px #6592CF;
    border-radius: 50%;
    left: calc(50% - 125px);
    top: calc(50% - 125px);
    background: #243D83;
  }

  .main > div > div {
	  width: 50px;
    height: 50px;
    margin: auto;
    border-radius: 50%;
    background: #EEB850;
  }
</style>
```
