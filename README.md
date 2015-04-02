# Chroma
Chroma is color conversion library that implements perceptually linear color spaces such as CIELab &amp; CIE-LCH.

*Documentation is work in progress.*

## Synopsis

## Motivation

Often in design process, the intent and methodology of color production relies on the predictibility of luminosity. Human vision has evolved to prioritize processing of luminosity information of the projected retinal image. Shape and form are processed before chromacity and hue. Artists & designers benefit from being able to control luminosity in a linear color space. It is pivotal in generating a visual hierachy for a variety of reasons such as distraction, emphasis, phase, depth, abstract artistic intents, etc.

Color spaces such as HSL, HSV/HSB and RGB are optimized for digital displays and lack luminosity control. For example, varying Hue while keeping Saturation and Lightness constant in HSL colorspace produces perceptually non-uniform colors. Moreover, Lightness is a non-linear function of both - Saturation and Hue. This severely limits the ability to predict the apparent and perceptual luminosity.

Chroma library allows for color production in CIE-Lab and CIE-LCH (cyclindrical transfomration of CIE-Lab) which are better suited for human vision and perceptual predictibility. Chroma objects can be instantiated with CIE color parameters, but represented and drawn in RGB color space.


Chroma is color conversion library that implements perceptually linear color spaces such as CIELab & CIE-LCH.

## Code Example



## Installation

#### How to install library Chroma


Install with the "Add Library..." tool

New for Processing 2.0: Add contributed libraries by selecting "Add Library..."
from the "Import Library..." submenu within the Sketch menu. Not all available
libraries have been converted to show up in this menu. If a library isn't there,
it will need to be installed manually by following the instructions below.


#### Manual Install

Contributed libraries may be downloaded separately and manually placed within
the "libraries" folder of your Processing sketchbook. To find (and change) the
Processing sketchbook location on your computer, open the Preferences window
from the Processing application (PDE) and look for the "Sketchbook location"
item at the top.

Copy the contributed library's folder into the "libraries" folder at this
location. You will need to create the "libraries" folder if this is your first
contributed library.

By default the following locations are used for your sketchbook folder:
For Mac users, the sketchbook folder is located inside ~/Documents/Processing.
For Windows users, the sketchbook folder is located inside
'My Documents'/Processing.

The folder structure for library Chroma should be as follows:

Processing
	libraries
		Chroma
			  examples
			  library
				    Chroma.jar
			  reference
			  src


Some folders like "examples" or "src" might be missing. After library
Chroma has been successfully installed, restart the Processing
application.


If you're having trouble, have a look at the Processing Wiki for more
information: http://wiki.processing.org/w/How_to_Install_a_Contributed_Library


## API Reference

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)
