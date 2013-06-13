Description:

	The Responsive LESS Boilerplate is a starting point for the development of mobile-first, responsive web sites. It was created by Ryan Roth, owner of  Dropseed Solutions, LLC (www.dropseedsolutions.com) to be used in the development of the business's responsive websites for client projects. The boilerplate's major components are:
	
		1. The Semantic Grid System (www.semantic.gs), a "page layout for tomorrow" which runs on LESS, SCSS or Stylus and boasts the creation of fixed, fluid, or responsive layouts without adding extra classes such as .grid_xx to your css.
		
		2. The Adaptive Images (www.adaptive-images.com) solution for responsive media, a combination of PHP and Javascript which automatically resizes and serves the proper images to the client depending on the screen size of the device. It does so with a mobile-first priority. I believe it is currently one of, if not the, best solution to the problem of mobile-first, responsive media.
			
	At its root, the boilerplate is an amalgation of different fantastic techniques developed by equally fantastic and talented designers and developers. They include:
		
		http://html5boilerplate.com/
		http://csswizardry.com/inuitcss/
		http://necolas.github.com/normalize.css/
		http://meyerweb.com/eric/tools/css/reset/
		http://getskeleton.com/
		http://semantic.gs/
		http://adaptive-images.com/
		http://html5boilerplate.com/mobile
		http://stuffandnonsense.co.uk/projects/320andup/
		http://cssgrid.net/
	
	I thank them all for their tireless commitment to quality, openness, and the community at large.
	
Usage:

	The usage of the boilerplate should be pretty self explanatory even to those with minimal experience with responsive design. It is as plug-and-play as possible. Some important notes:
	
		1. It is important to visit and read the usage of Adaptive Images. The Responsive LESS Boilerplate is set up for break-points at 1382, 992, 768, 600, and 480px device widths, which are visible in the style.less file. These break-points are preconfigured in the adaptive images php file. Adaptive Images caches any resized images in the /assets/images/ai-cache file which must be writable on the server. Your images are to be placed in the /assets/images file and are automatically resized and cached.
		
		2. All of your css or less is input in the /assets/stylesheets/style.less file. As a mobile-first solution, any css or less included outside of the media queries in this file is assumed to be for devices with a screen width up to 480px. You then add to it in the media queries that follow.
			
		3. The boilerplate includes certain things which are of course optional but which I have added under the assumption that you will remove them if not needed. These include the addition of Dublin Core meta tags, a sitemap.xml base, humans.txt, and a base robots.txt. You may find other things you don't need and feel free to remove them.
		
		4. It is essential that you visit and learn how to use the Semantic Grid System at www.semantic.gs. It is as simple as adding a single class to the element you wish to have fall into the grid. I highly suggest it as it is absolutely semantic and incredibly easy.

License:

	DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
                    Version 2, December 2004 

	Copyright (C) 2004 Sam Hocevar <sam@hocevar.net> 

	Everyone is permitted to copy and distribute verbatim or modified 
	copies of this license document, and changing it is allowed as long 
	as the name is changed. 

	DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
	TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

	0. You just DO WHAT THE FUCK YOU WANT TO. 
	
Support:

	I am always available for questions, comments, teaching, and any other things you may need. Feel free to contact me at any time via the following links and profiles:
	
		Twitter: @dropseed
		Email: ryan@dropseedsolutions.com
		Forrst: http://forrst.me/dropseed
		Zerply: http://zerply.com/dropseed/
		Google+: https://plus.google.com/103967706516142920525/posts
		Facebook: https://www.facebook.com/dropseed
		Github: https://github.com/dropseed
		
ENJOY!