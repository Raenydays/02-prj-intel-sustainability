<!-- Prompt 1 -->
 create an interactive webpage that highlights Intel’s sustainability goals in a timeline format.
 - Intel's logo should be clean and visible in the top left (intel-header-logo.svg) 
 - The main sustainability header should be centered in the page, with an darkened overlay over the /workspaces/02-prj-intel-sustainability/img/intel background splash.jpg
 - underneath this header the sustainability statement will be: Corporate Responsibility Is the Foundation of Our Business 
 - a line under will be: At Intel, corporate responsibility and innovation go hand in hand. For decades, we have set ambitious sustainability goals and embedded ethical practices across our global operations.
 under that will be: Explore Intel's journey through time, discovering how our commitment to innovation has shaped a more sustainable future for technology and our planet.
 - the timeline should be in the body below everything
 -  allow for users to be able to scroll horizonal showcasing every date (from 1968 to 2024) and events in 3 sections at a time each in the format: Date (top center), Short description (lower center), long description(bottom center)

<!-- Prompt 2 -->
Focusing on main header
tint the overlay into a glassy blue, changing the font color of the body into a readable white
-move the intel logo into its own header at the top of the page making this header a dark blue but keep it the same slightly translucent
use the font # Intel One Mono for the all headers

<!-- Prompt 3 -->
Focusing on Timeline
We want to add images into the timeline sections
-Each section focuses on a topic, of which there is a similarly named file in /workspaces/02-prj-intel-sustainability/img
-Add each image to its specific section, moving the information in the section into o hover/focus activated translucent overlay tinted a slight grey
-add a smooth transition to each overlay using and ease of .5 
-Fit each image to the size of the section allowing to be able to adjust with size
-Remove date from overlay and add it above each card in a clean line, using the same dark blue as the rest of the page for the background of the card ie. blue behind date, and white at the bottom of the card. Make the blue bar also slightly opaque
-add CSS Scroll Snap to the timeline
-darken scroll bar

<!-- prompt 4 -->
-clean up all html and css for redundancies
-any areas where sections could be simplified should be implemented with annotations to explain changes
-replace divs/nest divs with clear labels ie. li,ul,h1,h2...

<!-- Prompt 5 -->
Fixing layouts and fonts
-use the font Intel one mono for the statement line, doing the same for the card section dates and the Sustainability header
-Use the font Lato for the statement and explore
-Change both statement and main header to bold

<!-- Prompt 6 -->
Expand the background image used for the sustainability section throughtout the entire page (make it parent background). Keep the transparent blue tint overtop only the background.
-move the "Scroll to view timeline | Hover over cards to learn more!" info to slightly above the timeline keeping to the right
-change the white overlay to be a stage more transparent

<!-- Prompt 7 -->
Focused on viewports and different devices
Add media query allowing devices less than 600 pixels wide to change site
-Hero section: header should be moved 30 pixels up and made similar font size as statement line
-Timeline-info should be changed to "Touch to find out more
-Timeline should be shifted from horizontol scrolling to vertical scrolling
-in the media query remove the bottom white bar from the cards