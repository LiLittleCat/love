<h1 id="heart" style="visibility: visible;">💕</h1>
<h1 id="count"></h1>
<script type="text/javascript" language="javascript">
    function test() {
        window.setTimeout("test()", 1000);
        var second = 1000;
        var minute = second * 60;
        var hour = minute * 60;
        var day = hour * 24;
        var year = day * 365;
        var begin = new Date("2019-08-07").getTime();
        var now = new Date().getTime();
        var difference = now - begin;
        // 天数
        var days = Math.ceil(difference / day);

        document.getElementById("count").innerHTML = days + " days <br>have we been in love.";
    }
    test()
</script>

<!-- <script>
    function blinklink() { //参数是id，如果对你name比较熟悉，你可以改改代码换成name
        window.setTimeout("blinklink()", 1000);
        var id = document.getElementById("heart");
        if (id.style.display == 'none') { //none表示隐藏起来的意思，也就说如果这个元素是隐藏起来的话
            id.style.display = 'block'; //显示它
        } else { //否则
            id.style.display = 'none'; //隐藏它；
        }
    }
    blinklink();
</script> -->
<script>
    function blinklink() { //参数是id，如果对你name比较熟悉，你可以改改代码换成name
        window.setTimeout("blinklink()", 1000);
        var id = document.getElementById("heart");
        if (id.style.visibility == 'hidden') { //none表示隐藏起来的意思，也就说如果这个元素是隐藏起来的话
            id.style.visibility = 'visible'; //显示它
        } else { //否则
            id.style.visibility = 'hidden'; //隐藏它；
        }
    }
    blinklink();
</script>