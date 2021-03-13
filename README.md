# Team Shape Templates

Templates for popular drawing and diagramming tools to represent the team types and team interaction modes in Team Topologies.

Based on some of the ideas in the book _Team Topologies_ by Matthew Skelton [@matthewskelton](https://github.com/matthewskelton) and Manuel Pais [@manupaisable](https://github.com/manupaisable).

> See [teamtopologies.com](https://teamtopologies.com/) for more details about Team Topologies.

> Copyright © 2018-2021 [Team Topologies](https://teamtopologies.com/) - Licenced under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) ![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/3.0/88x31.png)

## Principals for using the shapes

When using the team shapes to create your own diagrams there are a number of constraints that should be applied:

- Team and X-as-a-Service shapes should be solid to represent their long-lived nature
- Collaboration and Facilitation shapes should be 50% transparency to represent the more short-lived nature of the interaction 
- Stream-aligned teams should never provide an X-as-a-Service directly
- Use diagrams as a starting point for meaningful discussion, they are visuals to drive conversations around needs and evolution
- Any diagrams you create will be a "snapshot" of your current landscape, use them to visualize and present potential issues that may need to be addressed

### Designed for color vision deficiency

The shapes have been designed with the specific intention of being usable by everyone including those that may have a color vision deficiency. For this reason, the following constraints should apply:

- Platform teams should always have square corners 
- Stream-aligned teams should always be horizontally aligned with rounded corners
- Enabling teams should always be vertically aligned with rounded corners
- Complicated subsystem teams should always be an octagon
- Collaboration should be indicated using a parallelogram
- Facilitation should be represented using a circle
- X-as-a-Service should be represented with a triangle, with the point of the triangle indicating the direction of the service being provided 

The following images were generated using this [color blindness simulator](https://www.color-blindness.com/coblis-color-blindness-simulator/):

|                  Normal                  |                            Proto                             |                           Deutero                            | Tritano                                                      | Monochrome                                                   |
| :--------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![Normal](resources/Shapes%20Normal.png) | ![Dichromatic Protanopia](resources/Shapes%20Dichromatic%20Protanopia.png) | ![Dichromatic Deuteranopia](resources/Shapes%20Dichromatic%20Deuteranopia.png) | ![Dichromatic Tritanopia](resources/Shapes%20Dichromatic%20Tritanopia.png) | ![Monochromatic Achromatopsia](resources/Shapes%20Monochromatic%20Achromatopsia.png) |

### Key differences from the shapes in the book 

The image below is an example of the shapes you may have seen in the book. You may notice that there are some clear differences between the shapes shown above and those you may have previously seen in the book. There are a number of reasons for this which are explained below.

|                         Book Shapes                          |                         Tool Shapes                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| ![Book shapes example](resources/Book%20shapes%20example.png) | ![Recreated book shapes example](resources/Recreated%20book%20shapes%20example.png) |

- The X-as-a-Service interaction is a grey triangle instead of two white bars joining the two teams. The reason for the difference here is two-fold, firstly the shape defined in the book does not indicate the direction of the interaction being provided, the point of the triangle now determines this.  Secondly, the shape representing the X-as-a-Service interaction in the book was very difficult to re-create in a number of different diagramming tools, using a simple triangle makes this much easier.
- The Collaboration interaction is a parallelogram instead of a hatched square - recreating the hatching in different diagramming tools was problematic so this was changed to use a parallelogram
- The Facilitation interaction mode is a plain circle instead of a circle with dots - recreating the dots in different diagramming tools was problematic so this was changed to use a circle

## Available Team Shapes

#### Currently supported

* All shapes for the four fundamental team types (Stream-aligned, Enabling, Complicated Subsystem, and Platform)
* X-as-a-Service, Collaboration and Facilitation interaction modes
* Flow of change

![Screenshot of Team Topologies shape library in diagrams.net](diagrams.net/2021-03-04--TT-drawing-shapes--diagrams_net.png)

The team shapes are currently available for the following tools:

### draw.io / diagrams.net

See [TeamTopologies.xml](diagrams.net/TeamTopologies.xml) in the _diagrams.net_ folder. This creates a Library with several shapes. The shapes are named - hover over a shape to see the description:

#### Usage

You have a couple of options, simply click the following link to pre-load the library:

- [Open Diagrams.net with the Team Topologies Shape Libray](https://app.diagrams.net/?splash=0&ui=min&clibs=Uhttps%3A%2f%2fraw.githubusercontent.com%2fTeamTopologies%2fTeam-Shape-Templates%2fmaster%2fdiagrams.net%2fTeamTopologies.xml)

Or

* Download _[TeamTopologies.xml](diagrams.net/TeamTopologies.xml)_ from this repository
* Open diagrams.net in a browser
* File -> Open Library from -> Device
* Select the file _TeamTopologies.xml_

A new shape library should appear. 

### Google Draw 

Open the template at [Team Topologies Template for modelling - Google Draw](https://docs.google.com/drawings/d/1MxEb1bm1tez0aLaufEHUgv5AO7d577lRC1xdEtAFr1Q/copy?usp=sharing) and choose _Make a copy_

Then copy/paste the shapes as needed into Google Draw or Google Slides if needed.

### Google Slides

Open the template at [Team Topologies Template for modelling - Google Slides](https://docs.google.com/presentation/d/1jEqC5PQNeK57E8zB31SecBYA5H1K0SmER5erLYPOn-0/copy#slide=id.p) and choose _Make a copy_

### PowerPoint

Download the template from the [Team Topologies Template for modelling - PowerPoint](powerpoint/Team%20Topologies%20Template%20for%20modelling%20-%20PowerPoint.pptx) and start editing as needed

### Miro

- Download the latest release of the [Team Topologies Template for modelling - Miro](https://github.com/TeamTopologies/Team-Shape-Templates/releases) package
- Open Miro and click on _Upload from backup_
- This will create a new board called _Restored Team Topologies template for modelling - Miro_
- Then simply rename the board and start using it by copy and pasting the different shapes as required

See the [Miro Readme](miro/readme.md) for more details on how to edit the shapes for Miro. 
