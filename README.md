# NASAWorldWind.github.io

NASA World Wind organization website

# Adding Content
1. Install Hugo
This site is generated by [Hugo](https://gohugo.io/). To use Hugo on your own machine, download the latest version of Hugo.
2. Use Archetyptes to create new content files
Hugo provides a mechanism called *front matter* which are key value properties to be defined in every content file. Using Hugo's archetypes will ensure the new content you are generating includes all of the expected properties. To utilize archetypes to generate a new tutorial for World Wind Android, just issue the following command from the root of the project:
```
$ hugo new tutorials/android/<tutorial name>.md
```
This will add the expected front matter. Some of the values may not be populated, but will have a default or empty value instead.
3. Write in Markdown
Author your content using markdown for formatting. Markdown allows for basic HTML. Advanced options are available through the use of [shortcodes](https://gohugo.io/extras/shortcodes/). See the Android download page for an applied example.
4. Observe your work live
Hugo can serve and automatically reload your work when you save. Simple run the following command from within the project directory to see live changes:
```
$ hugo serve
```

## License

    NASA WORLD WIND

    Copyright (C) 2001 United States Government
    as represented by the Administrator of the
    National Aeronautics and Space Administration.
    All Rights Reserved.

    NASA OPEN SOURCE AGREEMENT VERSION 1.3

    This open source agreement ("agreement") defines the rights of use, reproduction,
    distribution, modification and redistribution of certain computer software originally
    released by the United States Government as represented by the Government Agency
    listed below ("Government Agency"). The United States Government, as represented by
    Government Agency, is an intended third-party beneficiary of all subsequent
    distributions or redistributions of the subject software. Anyone who uses, reproduces,
    distributes, modifies or redistributes the subject software, as defined herein, or any
    part thereof, is, by that action, accepting in full the responsibilities and obligations
    contained in this agreement.

    Government Agency: National Aeronautics and Space Administration (NASA)
    Government Agency Original Software Designation: ARC-15166-1
    Government Agency Original Software Title: NASA World Wind
    User Registration Requested. Please send email with your contact information to Patrick.Hogan@nasa.gov
    Government Agency Point of Contact for Original Software: Patrick.Hogan@nasa.gov

    You may obtain a full copy of the license at:

        https://worldwind.arc.nasa.gov/LICENSE.html

