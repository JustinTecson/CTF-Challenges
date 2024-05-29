# Horsing-Around-at-Troy - easy 

## Description
* 
 * We have received a gift from the Gods! We praise them for this victory. Wait, did you hear that? Sounds like it came from within...
 * 

## Hint
* perhaps there is something inside 

## Knowledge or Tools Needed
* <knowledge or tools needed>
* steg tools, binwalk, 7zip maybe (just anything that can reveal files within files)

# Flag:
 `nicc{7Ro14-H1pPo2}`

## Credit:

* Developed by:	 BonsaiUmai

## Solution Steps
* For my solution at least, it was to use binwalk on the image of the trojan horse
* Other images would then be revealed within it - many identical image files of greek soldiers
* If viewing it purely from a terminal it would be immediately obvious that there is an image that has a different file size than all the others.
* This image is of Odysseus and the flag is present on the image.
* If the user was able to examine the contents with image previews, the flag finding would be much easier too. 
