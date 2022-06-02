<div class=" slider">
    <div class="slides">
        <!--radio buttons start-->
<input type="radio" name="radio-btn" id="radio1">
<input type="radio" name="radio-btn" id="radio2">
<input type="radio" name="radio-btn" id="radio3">
<input type="radio" name="radio-btn" id="radio4">
<!--radio buttons end-->
<!--slide images start-->
<div class="slide first">
    <img src="https://images.unsplash.com/photo-1586227740560-8cf2732c1531?ixlib=rb-1.2.1&ixid=MnwxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHwxfHx8ZW58MHx8fHw%3D&auto=format&fit=crop&w=500&q=60"
        alt="">
</div>
<div class="slide">
    <img src="https://images.unsplash.com/photo-1654041563290-2d6118dba2c6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw0fHx8ZW58MHx8fHw%3D&auto=format&fit=crop&w=500&q=60"
        alt="">
</div>
<div class="slide">
    <img src="https://images.unsplash.com/photo-1648737119247-e93f56878edf?ixlib=rb-1.2.1&ixid=MnwxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHw2fHx8ZW58MHx8fHw%3D&auto=format&fit=crop&w=500&q=60"
        alt="">
</div>
<div class="slide">
    <img src="https://images.unsplash.com/photo-1654004762137-0e4025b88119?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwxM3x8fGVufDB8fHx8&auto=format&fit=crop&w=500&q=60"
        alt="">
</div>
<!--slide images end-->
<!--automatic navigation start-->
<div class="navigation-auto">
    <div class="auto-btn1"></div>
    <div class="auto-btn2"></div>
    <div class="auto-btn3"></div>
    <div class="auto-btn4"></div>
</div>
<!--automatic navigation end-->
</div>
<!--manual navigation start-->
<div class="navigation-manual">
    <label for="radio1" class="manual-btn"></label>
    <label for="radio2" class="manual-btn"></label>
    <label for="radio3" class="manual-btn"></label>
    <label for="radio4" class="manual-btn"></label>
</div>
<!--manual navigation end-->
</div>
<!--image slider end-->

<script type="text/javascript">
    var counter = 1;
    setInterval(function () {
        document.getElementById('radio' + counter).checked = true;
        counter++;
        if (counter > 4) {
            counter = 1;
        }
    }, 5000);
</script>