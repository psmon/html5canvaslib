Welcome to the html5canvaslib wiki!

# Intro
이거슨 html5 를 손쉽게 제어하는 LIB

# How To SetUp
in Header

    <script src="http://psmon.x-y.net/pscoco/lib/cocos2d-beta2.js"></script>
    <script src="http://psmon.x-y.net/pscoco/lib/pscoco.js"></script>

in Body
    
    <div id="psmon-demo" style="width: 600px; height: 480px;float: left;"></div>
    <script type="text/javascript">
    var cocoApp=null;
    cocoApp= new Application('psmon-demo',"gray");
    cocoApp.run();
    // Your Code Here
    </script>


# Your Code
    
    var img2 = cocoApp.addImage('assets/ball1.png', 120,100, false);
    img2.seqTo([
        {x:100,y:122,duration:0.3,angle:5 },
        {x:250,y:50,duration:0.3,angle:45 },
        {x:300,y:300,duration:0.3,angle:90 ,opacity:50,scale:0.5}
    ]);

# More Sample

http://psmon.x-y.net/pscoco/sample.html
