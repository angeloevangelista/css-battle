# Target #002 - Carrom

## Objective

<div align="center">

![Target #002 - Carrom](./.github/images/002.png)

</div>

## Code

```html
<div class="container">
  <div class="top-left"></div>
  <div class="top-right"></div>
  <div class="bottom-right"></div>
  <div class="bottom-left"></div>
</div>

<style>
  body {
    margin: 0;
    position: relative;
  	background: #62374e;
  }

  .container > div {
    position: absolute;
    width: 50px;
    height: 50px;
    background: #fdc57b;
  }

  .top-left {
	  top: 50px;
    left: 50px;
  }

  .top-right {
	  top: 50px;
    right: 50px;
  }

  .bottom-right {
	  bottom: 50px;
    right: 50px;
  }

  .bottom-left {
	  bottom: 50px;
    left: 50px;
  }
</style>
```
