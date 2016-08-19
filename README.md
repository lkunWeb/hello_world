# hello_world
* 第一次使用github
 * 感到一片茫然
 ```
 <script>
    // 1. 获得要操作的对象
    var inputs = document.getElementsByTagName("input");
    // 遇排它，必循环 双层循环(嵌套循环)
    for(var i=0;i<inputs.length;i++){
        // 循环遍历每一个input标签，然后注册点击事件
        inputs[i].onclick = function(){    // 注册事件时的当前对象一定要用this来表示
            for(var j=0;j<inputs.length;j++){  // 循环遍历每一个input标签
                inputs[j].style.backgroundColor = ""; // 将所有的标签背景颜色全部清空
            }
            this.style.backgroundColor = "red"; // 设置自己的背景颜色变为红色
        }
    }

    // 循环就是不停的做同一件事件
</script>
 ```
<script>
    // 1. 获得要操作的对象
    var inputs = document.getElementsByTagName("input");
    // 遇排它，必循环 双层循环(嵌套循环)
    for(var i=0;i<inputs.length;i++){
        // 循环遍历每一个input标签，然后注册点击事件
        inputs[i].onclick = function(){    // 注册事件时的当前对象一定要用this来表示
            for(var j=0;j<inputs.length;j++){  // 循环遍历每一个input标签
                inputs[j].style.backgroundColor = ""; // 将所有的标签背景颜色全部清空
            }
            this.style.backgroundColor = "red"; // 设置自己的背景颜色变为红色
        }
    }

    // 循环就是不停的做同一件事件
</script>
