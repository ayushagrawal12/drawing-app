<html>
    <head>
        <meta charset="utf-8">
        <title>Drawing App</title>
        <meta name="viewport" content="initial-scale=1.0, user-scalable=yes">
        <link rel="stylesheet" href="https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.4/themes/start/jquery-ui.css">
        <link rel="stylesheet" href="styling.css">
    </head>	

    <body>
        <!--title-->
        <div id="header">Drawing App</div>
        
        <!--title-->
        <div class="inputContainer">
            <!--color-->
            <div class="input" id="colorInput">
                <input type="color" list id="paintColor">
            </div>
            
            <!--size-->
            <div class="input" id="thicknessInput">
                <div id="circle"></div>
            </div>
            <div class="input">
                <div id="slider"></div>
            </div>
        </div>
        
        <!--canvas container-->
        <div id="container">
            <canvas id="paint" width="500px" height="400px"></canvas>
        </div>
        
        <!--buttons-->
        <div class="inputContainer2">
            <!--Erase-->
            <div class="input2">
                <span id="erase" class="button">Erase</span>
            </div>
            
            <!--Save-->
            <div class="input2">
                <span id="save" class="button">Save</span>
            </div>
            
            <!--Reset-->
            <div class="input2">
                <span id="reset" class="button">Reset</span>
            </div>
        </div>        
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <script src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.4/jquery-ui.min.js"></script>
        <script src="javascript.js"></script><br>&nbsp;
        <footer>
            <span>Created By <a href="#">SparshKharya</a> | &copy; 2021 All rights reserved.</span>
        </footer>
    </body>
</html>
