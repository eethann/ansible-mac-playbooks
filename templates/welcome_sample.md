<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Welcome</title>
    <style>
    /* normalize.css */
    html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}body{margin:0}article,aside,details,figcaption,figure,footer,header,hgroup,main,nav,section,summary{display:block}audio,canvas,progress,video{display:inline-block;vertical-align:baseline}audio:not([controls]){display:none;height:0}[hidden],template{display:none}a{background:transparent}a:active,a:hover{outline:0}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:bold}dfn{font-style:italic}h1{font-size:2em;margin:0.67em 0}mark{background:#ff0;color:#000}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-0.5em}sub{bottom:-0.25em}img{border:0}svg:not(:root){overflow:hidden}figure{margin:1em 40px}hr{-moz-box-sizing:content-box;box-sizing:content-box;height:0}pre{overflow:auto}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}button,input,optgroup,select,textarea{color:inherit;font:inherit;margin:0}button{overflow:visible}button,select{text-transform:none}button,html input[type="button"],input[type="reset"],input[type="submit"]{-webkit-appearance:button;cursor:pointer}button[disabled],html input[disabled]{cursor:default}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}input{line-height:normal}input[type="checkbox"],input[type="radio"]{box-sizing:border-box;padding:0}input[type="number"]::-webkit-inner-spin-button,input[type="number"]::-webkit-outer-spin-button{height:auto}input[type="search"]{-webkit-appearance:textfield;-moz-box-sizing:content-box;-webkit-box-sizing:content-box;box-sizing:content-box}input[type="search"]::-webkit-search-cancel-button,input[type="search"]::-webkit-search-decoration{-webkit-appearance:none}fieldset{border:1px solid #c0c0c0;margin:0 2px;padding:0.35em 0.625em 0.75em}legend{border:0;padding:0}textarea{overflow:auto}optgroup{font-weight:bold}table{border-collapse:collapse;border-spacing:0}td,th{padding:0}
    * { font-size: 9pt;}
    body { width: 6in; margin: 0.75in auto;}
    table { margin-left: 2em; width: 55%;}
    tr { vertical-align: top; }
    th { text-align: left;}
    td { text-align: left;padding: 0.25em 0;}
    td:last-child { padding-bottom: 1em;}   /* hack for table spacing in text-edit */
    </style>
</head>
<body>


### Your Accounts

The account login for your computer is:

<table>
    <tr>
        <th align="left">username</th>
        <th align="left">password</th>
    </tr>
    <tr>
        <td align="left"><code>{{ username }}</code></td>
        <td align="left"><code>{{ password }}</code></td>
    </tr>
</table>

Most all our services can be accessed using this password and username. Please keep your password private.


### File Server Access
Our file server can be accessed with the above login. To connect to the server, choose **Connect to Server...** from the Finder's **Go** menu. The server's address is: <a href="{{ fileserver_address }}">{{ fileserver_address }}</a>

Please see the *Server and File Name Conventions* document for more information about where to put files on the server and how they should be named.


### Email
Your email is already set up on your computer. Below are the settings you'll need to access your email account from other devices. Our email uses Exchange and should auto-configure with these settings:


<table>
    <tr>
        <th align="left">address &amp; username</th>
        <th align="left">password</th>
    </tr>
    <tr>
        <td align="left"><code>{{ username }}@example.com</code></td>
        <td align="left"><code>{{ password }}</code></td>
    </tr>
</table>

Webmail can be accessed at <a href="{{ webmail_url }}">{{ webmail_url }}</a>, login with your full email address and password.


### Confidentiality & Social Networks

Our work is created under strict confidentiality agreements with our clients. Do not share or upload any pre-release work or images from pre-release work to Behance, Instagram, Pinterest, Twitter, Facebook or any other social networks.


### Wi-Fi
Our wireless network password is:  `{{ wifi_password }}`


### Google Apps
Our Google Apps URL is <a href="{{ google_apps_url }}">{{ google_apps_url }}</a>. Login with your email address and password.

</body>
</html>