<h1> HTML - Moving Banner </h1>

<h2> Description </h2>
I created this moving banner to enhance the look of my website
<br />


<h2> Features </h2>
- <b>shows a few of my skills in a continous banner.<b>
 <br />

<h2> Functionality </h2>
this is to enhance the look of my website by adding some moving text
<br /> 


<h2>Environments Used </h2>
<b>HTML</b>

<h2> The Script</h2>
<p align="center">

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #EDEDED;
            font-family: Arial, sans-serif;
        }
        .marquee-container {
            overflow: hidden;
            white-space: nowrap;
            box-sizing: border-box;
            width: 100%;
            background-color: #EDEDED;
        }
        .marquee {
            display: inline-block;
            white-space: nowrap;
            animation: marquee 15s linear infinite;
        }
        .marquee span {
            padding: 0 2rem;
            font-size: 1.5rem;
        }
        @keyframes marquee {
            from { transform: translateX(0); }
            to { transform: translateX(-50%); } /* Adjusted to increase speed */
        }
    </style>
</head>
<body>
    <div class="marquee-container">
        <div class="marquee">
            <span>Defender</span>
            <span>Intune</span>
            <span>Entra</span>
            <span>Cisco Umbrella</span>
            <span>Mimecast</span>
            <span>Defender</span> <!-- Repeated to ensure continuous loop -->
            <span>Intune</span>
            <span>Entra</span>
            <span>Cisco Umbrella</span>
            <span>Mimecast</span>
        </div>
    </div>
</body>
</html>

<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
