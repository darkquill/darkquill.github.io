<!DOCTYPE html>
<html>

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body {
            margin: 0;
            font-family: Century Gothic;
            color: #000000;
            font-size=30px 30px;

        }

        .topnav {
            position: relative;
            color: #000000;
            overflow: hidden;
            background-color: #FFFBCD;
        }

        .topnav a {
            float: left;
            color: #000000;
            text-align: center;
            padding: 9px 16px;
            text-decoration: none;
            font-size: 6px;
        }

        .topnav a:hover {
            background-color: hsla(43, 100%, 85%, 0.9);
            color: black;
        }

        .topnav a.active {
            background-color: hsla(43, 100%, 85%, 0.9);
            color: white;
        }

        .topnav-right {
            float: right;
            color: #000000;
        }

        /* Responsive navigation menu (for mobile devices) */

        @media screen and (max-width: 844px) {
            .topnav a,
            .topnav-right {
                display: block;
                float: right;
                color: #000000;
                text-align: left;
                padding: 5px 10px;
                text-decoration: none;
                font-size: 6px;
            }

            @media screen and (max-width: 844px) {
                .piss,
                .bio {
                    display: block;
                    float: center;
                    color: #000000;
                    text-align: center;
                    padding: 5px 10px;
                    text-decoration: none;
                    font-size: 6px;

                }

                .topnav-centered a {
                    position: relative;
                    top: 0;
                    left: 0;
                    color: #000000;
                    transform: none;
                }
            }
    </style>
</head>

<body>

    <!-- Top navigation -->
    <div class="topnav" style="color: #000000;">

        <!-- Left-aligned links (default) -->
        <a href="https://www.instagram.com/dark.quill/"><img src="https://cdn1.iconfinder.com/data/icons/social-media-rounded-corners/512/Rounded_Instagram_svg-512.png" alt="Instagram" style="width:25px;height:25px;"></a>
        <a href="https://www.facebook.com/profile.php?id=100083801345003"><img src="https://cdn1.iconfinder.com/data/icons/social-media-circle-7/512/Circled_Facebook_svg-512.png" alt="Facebook" style="width:25px;height:25px;"></a>
        <a href="https://twitter.com/QuillDark"><img src="https://cdn1.iconfinder.com/data/icons/social-media-rounded-corners/512/Rounded_Twitter5_svg-512.png" alt="HTML tutorial" style="width:25px;height:25px;"></a>
        <a href="https://www.pinterest.ph/darkquillblogs/"><img src="https://cdn1.iconfinder.com/data/icons/social-media-rounded-corners/512/Rounded_Pinterest2_svg-512.png" alt="Pinterest" style="width:25px;height:25px;"></a>
        <a href="https://contacts.google.com/person/c6279711328437725908"><img src="https://cdn4.iconfinder.com/data/icons/aiga-symbol-signs/612/aiga_mail_bg-512.png" alt="Email" style="width:25px;height:25px;"></a>

        <!-- Right-aligned links -->
        <div class="topnav-right">
            <a href="#home" class="active" style="color: #000000;font-size:20px;">Home</a>
            <a href="#about" style="color: #000000;font-size:20px;">About</a>
            <a href="#about" style="color: #000000;font-size:20px;">Contact</a>
        </div>
    </div>

    <style>
        .logo {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 260px;

        }
    </style>
    </head>

    <body>

        <div class="logo">
            <a href="default.asp" style="text-align:center;">
<img style="width:330px;height:200px;text-align:center;" src="https://media-private.canva.com/u3cCE/MAFGlGu3cCE/1/tl.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJWF6QO3UH4PAAJ6Q%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T054953Z&X-Amz-Expires=43745&X-Amz-Signature=30a47b4a39714838d0f659effec45be55cb19cebbbe8d5ba5fc3d884d73a591d&X-Amz-SignedHeaders=host&response-expires=Mon%2C%2018%20Jul%202022%2017%3A58%3A58%20GMT" alt="Website Logo"></a>
        </div>
        </div>

        <style>
            .piss {
                display: flex;
                justify-content: center;
                align-items: center;
                height: 0px;
                font-family: Alta;
                font-size: 21px;

            }
        </style>
        </head>

        <body>

            <div class="piss">
                <p>A JOURNEY TO LITERATURE</p>
            </div>

            <style>
                .bio {
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    text-align: center;
                    height: 77px;
                    font-family: Default;
                    font-size: 15px;

                }
            </style>
            </head>

            <body>

                <div class="bio">
                    <p>Bringing more insights into classic and modern literature to all. Blogs ranging from books, poetry, and journalism.<br>
                    </p>
                </div>

                <!-- IMAGE LINKS -->
                <p style="text-align:center;font-family:Century Gothic;font-size:15px;height:3px;color:#4D4D4D;"><b><u>CLICK THE IMAGES BELOW TO OPEN</b></u>
                </p>
                <style>
                    * {
                        box-sizing: border-box;
                    }

                    .column {
                        float: left;
                        width: 33.33%;
                        padding: 5px;
                    }

                    /* Clearfix (clear floats) */

                    .row::after {
                        content: "";
                        clear: both;
                        display: table;
                    }

                    .middle {
                        transition: .5s ease;
                        opacity: 0;
                        position: absolute;
                        top: 515px;
                        left: 17%;
                        transform: translate(-50%, -50%);
                        -ms-transform: translate(-50%, -50%);
                        text-align: center;
                    }

                    .column:hover .image {
                        opacity: 0.5;
                    }

                    .column:hover .middle {
                        opacity: 1;
                    }

                    /* Responsive layout - makes the three columns stack on top of each other instead of next to each other*/

                    @media screen and (max-width: 500px) {
                        .column {
                            display: flex;
                            justify-content: center;
                            align-items: center;
                            width: 100%;

                            @media screen and (max-width: 500px) {
                                .logo {
                                    display: flex;
                                    justify-content: center;
                                    align-items: center;
                                    height: 260px;

                                }
                </style>
                </head>

                <body>

                    <div class="row">
                        <div class="column">
                            <a href="ADD A LINK" title="Click to open">
  <img src="https://media-private.canva.com/5QoII/MAFGwJ5QoII/1/tl.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJWF6QO3UH4PAAJ6Q%2F20220717%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220717T142913Z&X-Amz-Expires=81264&X-Amz-Signature=c8ac143992ff38535e213bf73e549c5c48442d49e8e1c95136b2d11b35cb5e96&X-Amz-SignedHeaders=host&response-expires=Mon%2C%2018%20Jul%202022%2013%3A03%3A37%20GMT" alt="Click To Open" class="image" style="width:100%" title="Click to open"></a>
                        </div>
                        <div class="column">
                            <img src="https://media-private.canva.com/IfzlY/MAFGwJIfzlY/1/tl.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJWF6QO3UH4PAAJ6Q%2F20220717%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220717T192536Z&X-Amz-Expires=62637&X-Amz-Signature=1cf5ba26e699c74b9ed18ff895976abc9bd8c1f3910a65054849e06655dc0681&X-Amz-SignedHeaders=host&response-expires=Mon%2C%2018%20Jul%202022%2012%3A49%3A33%20GMT" alt="Click To Open" class="image" style="width:100%" title="Click to open">
                        </div>
                        <div class="column">
                            <img src="https://media-private.canva.com/zdobg/MAFGwJzdobg/1/tl.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJWF6QO3UH4PAAJ6Q%2F20220717%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220717T124205Z&X-Amz-Expires=87391&X-Amz-Signature=de97569b6386ecaeb30deb5d8ab96c0e0bddf3ccfc822136369745a203e09eff&X-Amz-SignedHeaders=host&response-expires=Mon%2C%2018%20Jul%202022%2012%3A58%3A36%20GMT" alt="Click To Open" class="image" style="width:100%" title="Click to open">
                        </div>
                    </div>

                </body>

</html>
