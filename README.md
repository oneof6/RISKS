<html>

<head>
    <title>main</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style type='text/css'>
        body {
            font: 14px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            color: whitesmoke;
            margin: 20px;
            padding: 20px;
            /*text-align: center;*/
        }

        a {
            color: #2ccff0;
        }
        
        img {
            width: 150px;
            height: auto;
            /*to preserve the aspect ratio of the image*/
        }

        table {
            border: 5px solid transparent;
            border-collapse: separate;
            border-spacing: 1em 10px;

        }

        td {
            background: rgba(100, 55, 100, 0.75);
            width: 10%;
            border-radius: 10px;
        }

        p {
            white-space: pre-wrap;
            overflow-wrap: break-word;
        }

        .sidenav {
            height: 100%;
            width: 150px;
            position: fixed;
            z-index: 1;
            top: 0;
            left: 0;
            background: rgba(0, 19, 28, 0.75);
            overflow-x: hidden;
            padding-top: 20px;
        }

        .sidenav a {
            padding: 6px 6px 6px 32px;
            text-decoration: none;
            font-size: 18px;
            color: #2ccff0;
            display: block;
        }

        .sidenav a:hover {
            color: #f1f1f1;
        }

        .main {
            margin-left: 200px;
            /* Same as the width of the sidenav */
        }

        @media screen and (max-height: 450px) {
            .sidenav {
                padding-top: 15px;
            }

            .sidenav a {
                font-size: 18px;
            }
        }
    </style>
</head>

<body background="images/space.jpg">

    <div class="sidenav">
        <a href="#">#main</a>
        <a href="#">#architecture</a>
        <a href="frameworks.html">#frameworks</a>
        <a href="#">#development</a>
    </div>
    <div class="main">
        <h2 style="color: #9ce1f8;">[R]educed [I]nformation [S]et [K]nowledge [S]ystem</h2>
        <p>This main page contains a general overview of the system content.</p>
        <table>
            <tbody>
                <!-- content block -->
                <tr>
                    <td>
                        <p>
                            <img src="images/refresh.png" align=left>
                            #refresh
                            As this page is heavily updated in the background, it is a good idea to refresh the whole page without using the browser cache.
                            In order to do this, hold the shift key down and hit the refresh icon (firefox).
                        </p>
                    </td>
                </tr>
                <!-- block end -->
            </tbody>
        </table>
    </div>
</body>

</html>
