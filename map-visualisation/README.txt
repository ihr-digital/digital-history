Method for the design of the map visualisation
---

Planning to visualise an XML version of the Post office directory on to a street map starts with a discussion about what we want to achieve generally - combine the individual buildings along the postman walk onto the map image, and then annotate some aspect of the data, somehow. After a brief brainstorm, using the map of the specific street we planned to visualise, Beaufort Street, we came up with some ideas about how to draw the buildings onto of the map and colourise the buildings according to either gender or occupation type. One of the requirements is that the visualisation will be printed in greyscale, so all graphic design steps needed to ensure the visualisation would still be understandable in both colour and greyscale.

We then began by gathering various digital files ('assets' in graphic design terminology) and putting these into a directory. This includes the map images themselves, the page scans of the Post Office directory and the XML data.

The graphic design application we planed to is called Affinity Designer. We decided to use this because it is reasonably priced, not a cloud based subscription, and combines both vector and raster based image editing features into a single application, and we wanted to learn to use some of the features of this new application. So a new Affinity Designer document was created and the digital assets placed into layers in the document.

As we began to crop each street walk and align it over the top of the map we realised the orientation of the map needed to be adjusted. To ensure we used the correct compass north, we found Beaufort street on the Apple Maps application, took a screenshot of the compass, imported the image onto our old map and rotated all the assets into a rough alignment position for the first version.

We then proceeded to draw building outlines along each of the street blocks, and cropped, overlayed and scaled the property numbers from the post office directory text, to help get a sense of the size of each building. This informed the drawing of the building/terrace walls. We originally used red lines to make them stand out more, but converted the lines to black later.

The background map includes more of the surrounding streets, which are not the focus of the visualisation and so we feathered/blurred the edges out to maintain attention on the Beaufort high street.

Now that the building artwork has been generated to scale, we decided which features to use such as the colour coding for each of the buildings. We decided to encode colors for gender, and use pink for Male and blue for Female (because pink/blue colours were not promoted as gender signifiers until just before World War 1 [https://www.smithsonianmag.com/arts-culture/when-did-girls-start-wearing-pink-1370097/])

The vector shapes of the buildings were duplicated into a second layer and rasterised (which means the shapres were transformed into pixels) then each block could be filled with the appropriate colour, according to Honorific, or if an Honorific was not present in the street walk, we made a judgement based on the persons name (In general the text identifies females explicitly and males implicity). There was one address which listed both a male and female and for this we simply painted both colours into the space. Once the colours were filled we needed to emphasise that these shapes were 'atop' the map, and so a drop shadow was added. The greyscale variant was checked to ensure that the saturation between the blue/pink colour codes was distinct enough to be identifiable when viewed or printed in greyscle and the colours were adjusted until it was.

Some organisation of the layers and grouping of assets in the Affinitiy designer document was performed, to make it easier to switch between the colour and greyscale variations of the visualiation. The mechanism of 'layers' in the application really helps, as you can make some layers visible or invisible, but maintain the common layers and their common object positions.

We then continued to iterate to include additional information about the occupations, and so designed visual connections, with outlines connecting the colour coded buildings to the digitised text of the post office directory. This was to ensure that the visualisation maintained as much information as possible and linked it together visually. Some futher adjustments, feathering and cropping of the background maps were applied, to continue to focus on the high street and now it is possible to see which groups of buildings contained which occupations.

The next piece of information to include in the visualisation somehow was the XML data. We had already included the scanned text from the book, drawn the buildings (and got a sense of their spacial density) and so including the transcribed version of each <addr> would have been a redundant addition to the graphic, thereby introducing too much visual noise (in our subjective opinons!). However, the directory contains street markers and we have not included those yet, so it seemed like a great and natural way to integrate the XML into the visualistion, as a sort of "digital background structure". We placed text boxes of the XML snippets into the spaces between the bubbles and included the transcription of the header to emphasise (or hint) that all the text was transcribed and not just the street markers. We deliberately used the Courier monospaced font because of the old school typewritten aesthetic, to ensure the XML code contrasted with the typography of the original source document's type.

At this point, the visualisation was shown to and discussed with colleagues and feedback was gathered.

The final version 6 was then created, correcting glitches with the buildings, neatening up the document layers, the visually connected bubbles and any text and text box alignment etc. The layout was tightened up even more to fit the publisher specificatinos for our printed book page size, and a legend was added in the whitespace at the top left (Can you guess the font used for the legend's label?). This position 'feels like' a good and pragmatic location because the viewer's eye will naturally observe the legend as their eye tracks down the page after reading the title. Observers of this visualisation should therefore be firstly 'primed' to comprehend the gender colour coding, and secondly to comprehend the building shapes aligned along the high street.



Version 1
- Gather assets - colour/grey map, compases, page scans.
- Place into Affinity Designer. Start to think about compositions of elements and positions on map.
- Screencapture from Apple Maps to get compass direction - rotate and align 3 compasses to correct orientation.
- Experiment with layer overlay settings for compasses to blend with colour/grey background maps.
- Cut up directory street walks and position in road segments. Rotate and scale to give an idea of building distribution.
- Realise that it is easier to rotate the map to place segments.


Version 2
- Draw in building outlines (use red colour to aid drawing on top of grey/colour background map).
- Add building/terrace walls (this is forming the representation for tight/narrow properties, as well as the A/B Flats with two coexisting occupants in a single property).
- Crop the walk numbers and align with the building walls to check the right number of properties - starting to see how some road sections are denser than others.
- Feather map background to emphasise the main high street. Side roads are ancillary to the visuation and just visual noise - blue these out?
- Reposition streetwalk columns to west/east side.


Version 3
- Determine which feature to use to colour code the buildings - gender.
- Gode gender to Pink for Male and Blue for Female.
- Rasterise building vectors into separate layer - flood fill the houses according to Honorific (or if Honorific not present in street walk, make judgement based on person name).
- Change stroke to black, add dropshadow to add visual height to the buildings as something atop the base map.
- Check greyscale variant - add layer to desaturate gender colours and ensure these look distinct when greyscale (this is what will be printed in the book).
- Rearrange layers in Affinity designer to make it easy to enable/disable greyscale/colour variants, by turning on/off 2 layers. This speeds up design iterations.


Version 4
- Split the postal walks image up even more, remove full listings, start to align and position in columns beside map.
- Change map feather to reduce amount of map which is visiable/relevant.
- Draw bubbles/outlines to visually connect the page segments to their map/building segments. The visual connection is important because it draws the eye from the source to the building/gender coded visuals (and Ted Nelson is one of my greatest influences ;-) ).
- Add semi transparency to the bubbles to obscure more of the background map. This de-emphasises the street details even more.
- Check greyscale looks okay.


Version 5
- We digitised the street directory to XML, so bring this asset in and integrate the XML representation into the visualiation - we now have 1) page scan, 2) map, 3) building, 
4) gender and 5) XML data assets all spatio-visually integrated into a single visualisation diagram.
- Realise the most appropraite content component of the XML is the heading and street markers, and these fit naturally between the previous work.
- Use courier font (old school digital aesthetic) and use <XML> tags - this gives the impression there is a 'background' representation of XML data.
- Show to colleagues - get feedback. Notice little glitches and correct.


Version 6
- Correct glitches, neaten building vector geometry.
- Tighten the whole layout to make it smaller and fit to the page. Remove more background map.
- Neaten up and align visually connected bubbles and texts.
- Add legend (in a nice whitespace at the top left, which is a good location because it prioritises the gender coding but it also happens to fill the space nicely - do you like this a-posteriori justification for the spatial arrangement of visual information?).
- Used the Comic Sans font for the legend labels deliberately!
