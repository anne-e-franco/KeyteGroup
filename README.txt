README

Author: Anne E. Franco
Client: KeyteGroup

Version: proof of concept - templating pending.

Technologies of note:
	Foundation3 - http://foundation.zurb.com/docs/
	"Off-Canvas" - http://www.zurb.com/playground/off-canvas-layouts
	Nivo-Slider - http://nivo.dev7studios.com/support/

Overview:
 Website for KeyteGroup refresh. This is a work in progress. home_template will serve as master for header/footer elements.

Navigation:
	the master for navigation is found in home_template. All links are "".
	There are 3 sets of navigation, and thus 3 places links must be updated: header, footer, and topMenu. topMenu is a navigation option which only appears on mobile, and narrow-width windows. 

Interior Pages:
 Templates for interior page elements will be included as partial html files whose contents should be added to the home_template, replacing the content between the following tags:
 		<!-- Begin Main Content --> <!-- End Main Content -->
 		
 

