# Chevron
![image](https://user-images.githubusercontent.com/88684972/185799495-72a6bb9e-78ae-4ed8-a58d-72f5a574ea0b.png)


## Solution
```html
<div class="arrow first"></div>
<div class="arrow second"></div>
<div class="arrow third"></div>
<style>
  body {
    background: #6592CF;
    margin: 0;
    
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  .arrow {
    position: relative;
    
    display: flex;
    align-items: center;
    justify-content: center;

    width: 250px;
    height: 100px;

    clip-path: polygon(0 0, 15% 0, 50% 70%, 85% 0%, 100% 0, 50% 100%, 0 0);
    
    background: #293D7E;
  }

  .first {
    top: 50px;
  }

  .third {
    bottom: 50px;
  }
</style>
```
