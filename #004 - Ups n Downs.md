# Target #004 - Ups n Downs

## Objective

<div align="center">

![Target #004 - Ups n Downs](./.github/images/004.png)

</div>

## Code

```html
<div class="down"></div>
<div class="up"></div>
<div class="down"></div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #62306D;
  }

  div {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
  }

  .down {
    margin-top: 100px;
    border-radius: 0 0 50% 50%;
  }

  .up {
    margin-bottom: 100px;
    border-radius: 50% 50% 0 0;
  }
</style>
```
