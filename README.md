# Seeed Fusion PCBA Open Parts Library: Component Library for KiCad

The Seeed Fusion Open Parts Libraries (OPL) and the associated component libraries are provided and maintained by the [Seeed Studio Fusion](https://www.seeedstudio.com/fusion.html) team and the wider community for the turnkey [Seeed Fusion PCB Assembly (PCBA) Service](https://www.seeedstudio.com/prototype-pcb-assembly.html). The OPL is a catalog of over 10,000 locally sourced components that can reduce costs and cut the production time of turnkey PCB assembly to just 7 working days. Find out more about the [Seeed Fusion PCBA service](https://www.seeedstudio.com/fusion.html). The catalog of available parts can be found [here](https://www.seeedstudio.com/opl.html).

To accelerate PCB design and make it much more convenient, Seeed Fusion has provided these component libraries for Eagle and KiCad. Prepared and scrutinized by our own engineers, these footprints can save you hours of design time and minimize potential production errors, so you can get on with PCB design with peace of mind. 

## Even More Components!

![](https://blog.seeedstudio.com/wp-content/uploads/2018/12/1200_628-facebook-ad-copy.png)

As of last December, the [OPL has expanded](http://www.seeedstudio.com/blog/2018/12/04/just-what-you-wanted-for-xmas-introducing-the-new-shenzhen-open-parts-library-with-over-10000-parts/) from 800 components to more than 10,000 with the introduction of the new Shenzhen OPL. The original Seeed OPL is a catalog of components from Seeed’s own inventory, we have the parts and, we have been using them in our own production processes for years. The Shenzhen OPL contains parts from Shenzhen’s biggest components distributor that Seeed can quickly order for turnkey PCBA. While the sources are different, both can be used together with the Seeed Fusion PCBA service and reduce the production time to 7 days.

But with all the new components and many more to come, we don’t have enough resources to create the footprints for all of them. So, we are asking for help from you and the wider community to gradually build-up the library with us. As more and more users utilize the OPL and update the component libraries, the better the library will become for everyone. 

![](https://gallery.mailchimp.com/0c272aa6642cc5d058579205f/images/33be2dbe-deda-4706-a83a-a15d25ab8264.png)

To assist with the process, we have designated a team of engineers to maintain the library and GitHub repositories. They will also help draw some footprints and connect schematic symbols. But while our engineers do their best to check each footprint, with the sheer number of components, it is inevitable that some errors will be present. It is unavoidable. So to make up for it, Seeed Fusion has introduced a re-manufacture promise: If an error in the library requires the boards to be re-manufactured, then we will re-manufacture the corrected boards for you for free. By using this library, you accept this potential risk.

## Footprint Design Guidelines
It is still early days, and we have a lot of catching up to do. So, the most important additions at this stage are unique symbols and footprints and any generic footprints that are missing. Part-specific symbols that use generic footprints and slight variations of generic footprints can be added later.

For consistency and ease of use, we would greatly appreciate it if everyone followed the same guidelines for new additions to the library:

-	The previous component libraries have been re-organized to match the Shenzhen OPL’s categorization. Please add new entries to the relevant sub-library according to the online OPL library’s classification.
-	Please take the time to study [KiCad’s own Library Convention](http://kicad-pcb.org/libraries/klc/) and ensure that the new footprints comply. Please refer to other footprints in the OPL or KiCad’s built-in footprints for reference. 
-	For MPN specific footprints, please follow the existing footprint naming convention for the footprint and name the corresponding schematic symbol with the manufacturer part number.

### Notes:
- #### The current version of the KiCad Library has been completely revamped in response to all the feedback we have recieved. Originally a direct import of the Eagle library, the old library did not comply with KiCad guidelines and placed features on the wrong layers. For the latest version, we have throroughly investigated the issues and revised (nearly) all of the footprints. Let us know if you think we missed something!

-	The Seeed OPL component libraries have been updated to match the Shenzhen OPL categories to aid in merging the two libraries. Some components will have moved to new homes, but this has not been updated on the website OPL library yet. We will update this soon!
-	Some of the original Seeed OPL KiCad component footprints have not been updated to match KiCad’s design guidelines yet. They are safe to use, and the pads are correct, but they may look a little ugly.
-	Unlike previous versions, we have uploaded the files individually as opposed to a whole zip file. We hope this will help you follow standard GitHub workflow to contribute changes. (Thanks for your feedback!)

There is a lot to consider in managing a large library like this, so we would greatly appreciate any ideas and feedback regarding how we can make the library more user-friendly. We’ll be monitoring the discussion section and the designated OPL section in our forums. You are also welcome to let us know by [e-mail](mailto:fusion@seeed.cc).

We hope the new maintained library will prove to be an invaluable resource to all of our PCBA users and beyond.

## Resources
1. A KiCad Bill-of-Materials (BOM) plugin to follow SeeedStudio's Fusion PCBA assembly service's template, This plugin is set up to use the KiCad schematic's part data as it is provided in Seeed Studio's Open Parts Library (OPL) collection for KiCad. - https://github.com/imrehg/kicad-bom-seeedstudio


[![Analytics](https://ga-beacon.appspot.com/UA-46589105-3/OPL_Kicad_Library)](https://github.com/igrigorik/ga-beacon)
