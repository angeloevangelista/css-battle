# Target #005 - Acid Rain

## Objective

<div align="center">

![Target #005 - Acid Rain](./.github/images/005.png)

</div>

## Code

```html
<div>
  <div class="down"></div>
  <div class="middle"></div>
  <div class="up"></div>
</div>
<style>
  body {
    background: #0B2429;
  }

  div > div {
    position: absolute;
    width: 120px;
    height: 120px;
    background: #F3AC3C;
  }

  .down, .middle {
    border-radius: 50% 0 50% 50%;
  }

  .down {
    z-index: 2;
	  left: calc(50% - 120px);
    bottom: calc(50% - 120px);
  }

  .middle {
    z-index: 1;
	  top: calc(50% - 60px);
	  left: calc(50% - 60px);
    background: #998235;
  }

  .up {
	  right: calc(50% - 120px);
    top: calc(50% - 120px);
    border-radius: 50%;
  }
</style>
```
