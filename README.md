# EV3 Hello World

[LEGO Mindstorms EV3](http://www.lego.com/en-us/mindstorms/products/ev3/31313-mindstorms-ev3/) Hello World in Scala

<table border="0">
  <tr>
    <td><a href="http://www.lejos.org/ev3.php">leJOS</a> </td>
    <td>0.8.1-beta</td>
  </tr>
  <tr>
    <td><a href="http://www.scala-lang.org">Scala</a> </td>
    <td>2.11</td>
  </tr>
</table>

## How to use

* install [leJOS](http://www.lejos.org/ev3.php) on EV3
* run `sbt assembly` to create executable `helloworld.jar` file
* connect EV3 via USB cable
* run `. deploy.sh` to deploy to EV3 Brick via USB connection
* on EV3 brick under leJOS select `Programs` > `helloworld.jar` > `Execute program`

![alt tag](https://dl.dropbox.com/s/1jl5x50z861h1dh/2014-04-22%2022.37.15.jpg)