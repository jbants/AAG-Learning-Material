# Lesson-1
## Create a webmap map

In this lesson we will be creating a basic webmap using the leaflet javascript library, basic HTML, and basic CSS. This lesson assumes little to no experiance with HTML, Javascript and/or CSS.

The intent of this lesson is to provide you with a basic handle on how to create a webmap and to understand the functions of the different components that make up a webmap. We will learn how to load data from different providers and will create vector geometry for displaying in the map.

You can think of HTML/Javascript/CSS like this; Picture a multi-use tower (apartments, officespace, retail). In the complex we have individual rooms for each use-type and each of those rooms are going to be styled differently and have different functions.

- HTML is the supporting structure of the complex (columns, girders, basement, roof).
- Javascript is the infrastructure (gaslines, power, internet, tv) and also determines what use-type a room will be and how that room will be used.
- CSS is the styling (carpets, paint, window dressings).

This is a pretty general analogy, since all three have the ability to do some part of each other. But for our purposes, this will suffice.

### Pre-requisites

The Operating System will not matter as all three (Windows, Mac, Linux/Unix) will display the same.

You will need a text editor for this tutorial. Notepad on Windows will work fine as will TextEdit on Mac. If you are on Unix/Linux, you are ahead of the game.
Personally, i like to use [SublimeText](https://www.sublimetext.com/) as it has syntax hilighting, different themes, and works on all three platforms. But choose what suites you best.

### Setup

Before we begin creating files lets create a folder to store our webmap.

1. Make a folder somewhere on your computer to use as a workspace.
> I'm creating mine at C:\Documents\James\Leaning_Material\Lesson1

All the code that I create for this lesson will be stored in here.
p
### HTML

We will create a basic skeleton for our webmap using HTML. HTML is simply a set of text tags which are interpreted by a web browser and tell it how to display. for example the tag ```<b> test </b> ``` tells the browser to stlye the text between the tags as bold <b>test</b>.

We will start out by creating a text file with an .html extension.

### Javascript

it is important to understand what makes up a webmap. The majority of webmaps we come across today allow for interaction with the user. Whether that be through 'slippy' maps (panning, zomming) or popups that show attributes.

Javascript is the language which allows for and drives this interaction. We could write our own javascript code to allow for all the interactions we could want, but that is way to hard and time consuming. Instead we include libraries in our application which give us the interaction we are looking for. These libraries have been tested quite extensively and are used around the world for webmapping. Two of the more prominent libraries are [Leaflet](http://leafletjs.com/) and [OpenLayers3](http://openlayers.org/). Both are excellent mapping ;ibraries.
Leaflet is a smaller in terms of size and has quite a large number of community generated plugins. OpenLayers has been around for a long time and has a rich history in the Free and Open Source Software (FOSS) Community. It also has a huge Application Programming Interface (API) which means that if you need to build a feature rich appliction and leaflet plugins dont do exactly what you are looking for, OpenLayers is probably your best bet.

For this tutorial we will be using leaflet since it is so easy to get up and going with.
