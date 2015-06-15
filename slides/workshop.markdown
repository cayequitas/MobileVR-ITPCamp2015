---
layout: slides
title: Getting started with VR on your mobile phone
---
<section markdown="block" class="title-slide">
# So . . . Let's get into Unity3D
{% include title-slide-footer.html %}
</section>

<section markdown="block">
## First we need to download the Unity Asset

if you guys have git installed, go ahead and type:
{% highlight bash %}
git clone https://github.com/googlesamples/cardboard-unity.git
{% endhighlight %}

if you don't here's the direct download link:
{% highlight bash %}
https://github.com/googlesamples/cardboard-unity/archive/master.zip
{% endhighlight %}


</section>


<section markdown="block">
### It's time to Rock N' Roll

Firts Let Get started on exporting everything to __ANDROID__ devices

did everyone get the __Android SDK__ ?


</section>

<section markdown="block">
### Using the Android Debug Bridge __ADB__

if you already downloaded the AndroidSDK you will have a folder call __platform tools__





</section>
<section markdown="block">

so we need to change directory to that folder in order to test the __ADB__ 

{% highlight bash %}
cd <path to your android sdk folder>/platform-tools

./adb devices

{% endhighlight %}

</section>
<section markdown="block">

if everything is doing good, we will export the path to ADB so we can do it globally with the terminal.

To export the path:

{% highlight bash %}
nano .bash_profile

export PATH=${PATH}:/<pathToTheAndroidSdkFolder>/android-sdk-macosx/platform-tools

{% endhighlight %}

</section>

<section markdown="block">
### Open Unity3D

we are going to import the cardboard asset we just downloaded
        * Go to Assets --> Import Package --> Custome Package
        * just click import

</section>

<section markdown="block">
### Let's check the Cardboard Asset

* double click it and navigate into the folder
* go to the DemoScene folder
* open the file with the Unity3D logo

</section>


<section markdown="block">
### Everything Working?

We can now try to export to your __Phone__

* So go ahead and type (Shift + Command + B)
* or just go to --> File --> Build Settings


</section>

<section markdown="block">
## We're almost there

* go down to the Player Settings - click it!
* then select the Resolution and Presentation 
* change the Default orientation to __Landscape Left__ (you can also do __Landscape Right__)


</section>

<section markdown="block">
## Let's try to Build it

* hit the Build and Run button 
* Unity is gonna ask you about where did you put the Android SDK
* keep calm - it's exporting everything to your phone!!!!!



</section>

<section markdown="block">
# Hello IOS


I've just only tryed this a few times with IOS so please be __PATIENT__ :)

</section>

