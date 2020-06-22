# HTML-CSS
SoftUni course from module "Frond-End" May 2020

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Media Icons</title>
    <style>
        @import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css");

        ul {
            display: inline-block;
        }

        ul,
        .fa {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        a {
            border-radius: 50%;
        }


        li {
            margin-left: 15px;
            display: inline-block;
            list-style: none;
            position: relative;
            height: 50px;
            width: 50px;
            -moz-border-radius: 50%;
            -webkit-border-radius: 50%;
            background-color: rgb(240, 240, 240);
        }

        .fa {
            color: black;
        }

        .fa:hover {
            cursor: pointer;
        }

        .fa-facebook-square:hover {
            color: rgb(66, 103, 178);
        }

        .fa-twitter:hover {
            color: rgb(29, 161, 242);
        }

        .fa-google-plus-circle:hover {
            color: rgb(219, 68, 55);
        }

        .fa-linkedin-square:hover {
            color: rgb(40, 103, 178);
        }

        .fa-instagram:hover {
            color: rgb(64, 93, 230);
        }
    </style>
</head>

<body>
    <ul>
        <li>
            <a href=""></a>
            <i class="fa fa-facebook-square fa-lg" aria-hidden="true"></i>
        </li>
        <li>
            <a href=""></a>
            <i class="fa fa-twitter fa-lg" aria-hidden="true"></i>
        </li>
        <li>
            <a href=""></a>
            <i class="fa fa-google-plus-circle fa-lg" aria-hidden="true"></i>
        </li>
        <li>
            <a href=""></a>
            <i class="fa fa-linkedin-square fa-lg" aria-hidden="true"></i>
        </li>
        <li>
            <a href=""></a>
            <i class="fa fa-instagram fa-lg" aria-hidden="true"></i>
        </li>
    </ul>
</body>

</html>
