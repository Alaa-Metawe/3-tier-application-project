For the Testing you may log into your ec2 instnces and put the below script and then try the loadbalancer link to test(Httpd Path /var/www/html/index.html)
########################################################################################################################
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3-Tier Application Test Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 50px;
        }
        h1 {
            color: #333;
        }
        p {
            color: #666;
            font-size: 1.2em;
        }
    </style>
</head>
<body>
    <h1>Welcome to the 3-Tier App!</h1>
    <p>This page is being served by the web server at:</p>
    <p><strong>Server Number 1//2</strong></p> // just put a number to test your loadbalancer performance 
    <p><strong>Thank You [SERVER_IP_ADDRESS]</strong></p>
    <p>This is a simple test to verify the application architecture is working.</p>
</body>
</html>
