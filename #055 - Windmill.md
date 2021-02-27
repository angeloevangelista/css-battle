# Target #055 - Windmill

## Objective

<div align="center">

![Target #055 - Windmill](./.github/images/055.png)

</div>

## Code

```html
<div>
  <div class="propeller-container yellow"></div>
  <div class="propeller-container blue"></div>
  <div class="propeller-container blue"></div>
  <div class="propeller-container yellow"></div>
</div>
<style>
  body {
    display: flex;
    align-items: center;
    justify-content: center;

    background-color: #191919;
  }

  body > div {
    display: grid;
    grid-template-columns: 1fr 1fr;
  }

  .yellow:before {
    background-color: #F9E492;
  }

  .blue:before {
    background-color: #4F77FF;
  }

  .propeller-container {
    position: relative;
    overflow: hidden;

    width: 100px;
    height: 100px;
  }

  .propeller-container:before {
    content: '';
    position: absolute;

    width: 100px;
    height: 100px;

    border-radius: 50%;
  }

  .propeller-container:nth-child(1):before {
    transform: translateY(50%);
  }

  .propeller-container:nth-child(2):before {
    transform: translateX(-50%);
  }

  .propeller-container:nth-child(3):before {
    transform: translateX(50%);
  }

  .propeller-container:nth-child(4):before {
    transform: translateY(-50%);
  }
</style>
```
