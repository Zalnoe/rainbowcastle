## Rainbow castle!
This is using the "github pages" feature, see https://pages.github.com/  
[See formatting guide](formatting-guide.md)

The published website can be seen at http://gitcases.github.io/rainbowcastle.  
You may need hard refresh (Ctrl+Shift+R) to see changes.


## The castle

<style type="text/css">
  .roof {
    border: 100px solid transparent;
    width: 200px;
    border-top: none;
    border-bottom-color: red;
    box-sizing: border-box;
  }
  .ground-floor {
    height: 500px;
    background: pink;
    width: 200px;
    position: relative;
  }
  .ground-floor > .door {
    background: white;
    position: absolute;
    bottom: 0;
    right: 50px;
    left: 100px;
    top: 100px;
  }
</style>

<div class="roof"></div>
<div class="ground-floor">
  <div class="door"></div>
</div>

<script>alert("Welcome to the rainbow castle");</script>
