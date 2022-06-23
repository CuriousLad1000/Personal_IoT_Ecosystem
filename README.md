# Personalized IoT ecosystem

## Introduction

The Internet of things is an idea of connecting your physical devices
(called things) to the internet to make them smarter and make your life
easier. An IoT ecosystem has devices connected to the internet or the
cloud. These devices collect the data such as temperature, pressure,
heart rate etc. and send it over to the cloud for processing and to gain
meaningful knowledge from it or to convert it into further automated
actions. Realising the huge potential in the technology, there has been
a boom in the organisations providing platforms and services oriented
towards the consumer IoT market.

## Purpose of the implemented system

### The problem:

In the current IoT market, considering the amount of revenue involved,
the companies/organization​s promote their personalized version of the
ecosystem​. The problem arises when the organizations close off their
ecosystem and prevents any external device or service to connect to
their ecosystem.

### The solution

The solution would be to look for existing community based open-source
ecosystems. We have built a prototype around one such platform which is
implemented on the existing hardware, this not only provides us with
personal data security but also eliminates the threat of vendor locking.

The system can easily be hosted on a low power computer such as a
raspberry pi and the connecting nodes can be programmed to communicate
with our server over the MQTT protocol.

The Home Assistant dashboard is highly customisable according to the
user's needs.

<br/>

<p align="Center">
  <img src="/osama.tasneem/Personal_IoT_Ecosystem/wiki/raw/images/cd9ca22b734e14377b292a22463abc663f17eaed.png">
</p>

<br/>

<p align="Center"> 
    <i>figure: a typical Home Assistant dashboard with "things" </i> 
<a href="https://magazine.odroid.com/article/home-assistant/">(src: Odroid)</a>

</p> 

## Project Objective

Build your own Private IoT Ecosystem that is free from the threat of
vendor locks and Silos.

## Hardware used

-   Raspberry Pi

-   ESP8266 based microcontroller *ESP01s*

-   Temperature and Humidity sensors

-   LEDs

-   WIFI Routers

## Software used

-   **IoT platform**: Home Assistant OS(HASSOS)

-   **Database server**: Home assistant(inbuilt)

-   **Communication Broker**: Mosqitto broker (MQTT)

-   **Programming Language and firmware platform used**: ESPHome,
    Arduino C/C++, python, scripting.

## Features offered

-   Server is hosted privately at home and hence, prevents any potential
    data breaches by third party.

-   The platform used provides very high level of interoperability and
    supports thousands of devices across hundreds of IoT brands.

-   No need to install multiple apps for different IoT devices.

-   This platform is a good attempt to retake the hold of data privacy
    and full control over the IoT infrastructure, since everything is
    hosted on our local server, the threat of vendor locking vanishes.

-   The Home Assistant dashboard is highly customizable according to the
    user's needs.

-   Our Home Assistant dashboard contains multiple sensors and actuator
    entities which can be controlled through either a mobile app or via
    web browser from any device.

For more details, please refer to the project's wiki

## Pictures (or refer to wiki)

**Dashboard home showing various sensors and camera feed.** (*Sensor
shows unknown because deep sleep is enabled on nodes to prevent battery
drain*)


<br/>

<p align="Center">
  <img src="/osama.tasneem/Personal_IoT_Ecosystem/wiki/raw/images/d2d9b88cd6173f157dab0796d855a6540feea4bd.png">
</p>

<br/>
<br/>

**Physical Nodes**

*Raspberry pi camera and server nodes*


<br/>

<p align="Center">
  <img src="/osama.tasneem/Personal_IoT_Ecosystem/wiki/raw/images/95b9d5f1851691fc85e3653442e262d46e1da56e.png">
</p>

<br/>
<br/>


<br/>

<p align="Center">
  <img src="/osama.tasneem/Personal_IoT_Ecosystem/wiki/raw/images/29580f7ac6276203d616f989e23ff359d364da47.png">
</p>

<br/>
<br/>

**Temperature nodes**


<br/>

<p align="Center">
  <img width="500" height="370" src="/osama.tasneem/Personal_IoT_Ecosystem/wiki/raw/images/914eabd92b4103b277a67e7f11df39e5015647d1.jpg">
</p>

<br/>
<br/>


<br/>

<p align="Center">
  <img width="500" height="370" src="/osama.tasneem/Personal_IoT_Ecosystem/wiki/raw/images/97a2a608284fc8795c3dd5d1f7c6dddebb2cb54d.jpg">
</p>

<br/>
<br/>

