<!DOCTYPE <html>
    <head>
        <style>
            body {
               background-color: black;
               position: absolute;
               left: 50%;
               top: 50%;
               -webkit-transform: translate(-50% , -50%);
               transform: translate (-50%, - 50%);
            }

            #earth {
                 width: 300px;
                 height: 300px;
                 background: url(https://shorturl.at/jluH8);
                 border-radius: 50%;
                 background-size:610px;
                 box-shadow: inset 8px 36px 80px 36px rgb(0,0,0),inset -6px 
                 0 12px 4px rgba(240, 238, 238, 0.3);
                 animation-name: rotate;
                 animation-duration: 5s;
                 animation-iteration-count: infinite;
                 animation-timing-function: linear;
            }

            @keyframes rotate{
                from{
                    background-position: 0px 0px;
                }
                to{
                  background-position: 610px 0px;   
                }    
            }
        </style>
    </head>
    <body>
        <div id="earth" ></div>
    </body>
</html>
