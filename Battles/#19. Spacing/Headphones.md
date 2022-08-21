# Headphones
![image](https://user-images.githubusercontent.com/88684972/185799576-93d1d1ef-04a9-433f-b57b-3a539a161dc3.png)

## Solution
```html
<div>
  <div class="headphones">
    <div class="ear left"></div>
    <div class="ear right"></div>
  </div>
</div>

<style>
  body {
    margin: 0;
    background: #293D7E;

    display: flex;
    align-items: center;
    justify-content: center;
  }

  .headphones {
    box-sizing: border-box;
    position: relative;
    bottom: 5px;
    
    width: 170px;
    height: 200px;

    border: 20px solid #6E91CA;
    border-radius: 85px 85px 30px 30px;
    border-bottom: none;
  }

  .ear {
    position: absolute;
    bottom: 0;
    
    width: 60px;
    height: 80px;
    
    background: #6E91CA;
    border-radius: 20px 20px 30px 30px;
  }

  .left {
    left: -20px;
  }
  
  .right {
    right: -20px;
  }
 
</style>
```
