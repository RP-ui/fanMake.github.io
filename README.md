<html>
    <head>
        <meta charset="UTF-8" content="Hooooo饭制工具1.0,人人都能轻松的作出自己心仪的游戏!">
        <link rel="shortcut icon" href="tree3-height.svg">
    </head>
    <body oncontextmenu="yj();return false;">
        <title>
            Hooooo饭制工具
        </title>
        <style>
            a{
                color:lightblue;
            }
            .btn-nav{
                border:none;
                border-radius:10px;
                background-color:lightgrey;
            }
            .btn-nav:hover{
                border:none;
                border-radius:10px;
                 background-color:grey;
            }
            .btn-yj{
                background-color:white;
                z-index:999;
            }
            .btn-yj:hover{
                background-color:lightgrey;
            }
            #wrr:focus{
                border:noen;
            }
            .dx{
                background-color:green;
                color:white;
                border-radius:5px;
                font-size:25px;
                width:5em;
                height:1.5em;
                border:none;
            }
            .dx:hover{
                opacity:0.8;
            }
            .dxnr{
                width:5em;
                border-radius:10px;
                border:solid;
                position:relative;
                left:2em;
                top:-2em;
            }
            .dxnr:hover{
                border:solid;
                border-color:green;
            }
            .dxbs{
                width:2em;
            }
            #sz:hover{
                transform:rotate(360deg);
                transition-duration:1s;
            }
        </style>
        <script>
            startMath=0;
            er=0;
            function findE(){

            }
        </script>
        <img src="tree33s.svg" width="15">
        <span id="yj"></span>
        <button class="btn-nav" onClick="startMath=startMath+1;startMathP();start();">运行</button>
        <button class="btn-nav" onClick="by();">编译</button>
        <button class="btn-nav">对象</button>
        <div id="ts" style="color:green;">
            <h3>调试控制台</h3>
            <br>
            <span id="startMath">运行次数:0</span><br>
            <span id="findE">失误操作:0</span><br>
            <br>
            <script>
                function startMathP(){
                    document.getElementById("startMath").innerHTML="运行次数:"+startMath;
                }
            </script>
        </div>
        <a name="sz"></a>
        <textarea id="wrrr" style="position:relative;top:999em;" cols="50" rows="10">
            <script>
                document.write("<span id='game'></span>");
                var game={};
                function creatGameWay(src,x,y,w,t){
                        document.getElementById("game").innerHTML=document.getElementById("game").innerHTML+"<img src='"+src+"' style='"+"position:fixed;left:"+x+";top:"+y+";z-index:"+t+";' width='"+w+"'>";
            }
                
            function creatGameTree(x,y,s,c,t){  
            if(game.math==1){
          document.getElementById("game").innerHTML=document.getElementById("game").innerHTML+"<img src='tree.svg' style='position:absolute;top:"+y+";left:"+x+";background-color:"+c+";z-index:"+t+";'"+" width='"+s+"'>";
            }            
            if(game.math==2.1){
          document.getElementById("game").innerHTML=document.getElementById("game").innerHTML+"<img src='tree2-1.svg' style='position:absolute;top:"+y+";left:"+x+";background-color:"+c+";z-index:"+t+";'"+" width='"+s+"'>";
            }    
            if(game.math==2.2){
          document.getElementById("game").innerHTML=document.getElementById("game").innerHTML+"<img src='tree2-2.svg' style='position:absolute;top:"+y+";left:"+x+";background-color:"+c+";z-index:"+t+";'"+" width='"+s+"'>";
            }    
            if(game.math==3.1){
          document.getElementById("game").innerHTML=document.getElementById("game").innerHTML+"<img src='tree3-width.svg' style='position:absolute;top:"+y+";left:"+x+";background-color:"+c+";z-index:"+t+";'"+" width='"+s+"'>";
            }    
            if(game.math==3.2){
          document.getElementById("game").innerHTML=document.getElementById("game").innerHTML+"<img src='tree3-height.svg' style='position:absolute;top:"+y+";left:"+x+";background-color:"+c+";z-index:"+t+";'"+" width='"+s+"'>";
            } 
           }

           function creatGameRect(x,y,w,h,c){
            document.write("<div style='position:fixed;left:"+x+";top:"+y+";width:"+w+";height:"+h+";background-color:"+c+";'></div>");
           }
function wait(a){
setTimeout(waitThings,a*1000);
}
var p={};
p.inner=null;
function pw(a){
    document.write("<"+a+">");
    document.write(p.inner);
    document.write("</"+a+">");
}
</script>
        </textarea>
        <a href="#"><button class="dx" style="position:relative;top:550em;">完成</button></a>
        <div id="wr" style="width:30em;height:50em;border:solid;border-color:lightgrey;position:absolute;left:8em;top:5em;">
            <textarea style="color:brown;font-size:25px;background-color:white;width:30em;height:50em;border:none;" id="wrr">
        
            </textarea>
            <div id="dx" style="position:absolute;top:0em;left:48em;width:10em;">
                <h3 style="color:red;">对象&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;<a href="#sz"><img src="sz.svg" id="sz" onClick=""></a></h3>
                <br>
                <br>
                    <img src="tree3-height.svg" class="dxbs">
                    <div class="dxnr">
                        <span>关卡-绿色风暴-树1🎗️🎫</span>
                    </div>
                    <button class="dx" onClick="document.getElementById('wrr').value=document.getElementById('wrr').value+'game.math=3.2;\ncreatGameTree(x:,y:,size:,color:,t:);\n';">调用</button>

                    <img src="tree2-1.svg" class="dxbs">
                    <div class="dxnr">
                        <span>关卡-冬天-树1</span>
                    </div>
                    <button class="dx" onClick="document.getElementById('wrr').value=document.getElementById('wrr').value+'game.math=2.1;\ncreatGameTree(x:,y:,size:,color:,t:);\n';">调用</button>

                    
                    <img src="tree.svg" class="dxbs">
                    <div class="dxnr">
                        <span>关卡-荒凉-树1</span>
                    </div>
                    <button class="dx" onClick="document.getElementById('wrr').value=document.getElementById('wrr').value+'game.math=1;\ncreatGameTree(x:,y:,size:,color:,t:);\n';">调用</button>

                    <img src="1-1.svg" class="dxbs">
                    <div class="dxnr">
                        <span>蜿蜒曲折的路--荒凉</span>
                    </div>
                    <button class="dx" onClick="document.getElementById('wrr').value=document.getElementById('wrr').value+'game.math=1;\n creatGameWay(src:,x:,y:,size:,t:);\n';">调用</button>

                    <img src="2-1.svg" class="dxbs">
                    <div class="dxnr">
                        <span>难度较大的路--冬天</span>
                    </div>
                    <button class="dx" onClick="document.getElementById('wrr').value=document.getElementById('wrr').value+'game.math=2.1;\n creatGameWay(src:,x:,y:,size:,t:);\n';">调用</button>
            </div>
            <script>
                var findEa=0;
                var str;
                function jc(){
                    document.getElementById("wrr").style.fontSize="40px";
                }
                function jx(){
                    document.getElementById("wrr").style.fontSize="16px";
                }
                function jz(){
                    document.getElementById("wrr").style.fontSize="25px";
                }
                function fff(){
                    findEa=findEa+1;document.getElementById('findE').innerHTML='失误操作:'+findEa;
                }
            function yj(){
                document.getElementById("yj").innerHTML="<div onClick='function l(){style.width=0;style.fontSize=0;};setTimeout(l,200);' style='position:fixed;width:5em;height:8em;border:solid;z-index:999;left:10em;'><div class='btn-yj' onClick='by();alert(str);'>查看编译后JS代码</div><div class='btn-yj' onClick='jc();'>放大</div><div class='btn-yj' onClick='jx();'>缩小</div><div class='btn-yj' onClick='jz();'>正常</div><div class='btn-yj' onClick='fff();'>取消</div></div>";
            }
                function by(){
                    str=document.getElementById("wrr").value;
                    str=str.replace(/Texthide/g, "style.fontSize=0");
                    str=str.replace(/hide/g, "style.width=0");
                    str=str.replace(/Imghide/g, "width=0");
                    str=str.replace(/get/g, "var");
                    str=str.replace(/gid/g, "document.getElementById");
                    str=str.replace(/plus/g, "document.write");
                    str=str.replace(/print/g, "console.log");
                    str=str.replace(/say/g, "alert");
                    str=str.replace(/<<</g, "/*");
                    str=str.replace(/>>>/g, "*/");
                    str=str.replace(/x:/g, "");
                    str=str.replace(/y:/g, "");
                    str=str.replace(/size:/g, "");
                    str=str.replace(/color:/g, "");
                    str=str.replace(/t:/g, "");
                }
                function start(){
                    window.open().document.write(document.getElementById("wrrr").value+"<script>"+str+"<\/script>");
                }
            </script>
        </div>
    </body>
</html>
