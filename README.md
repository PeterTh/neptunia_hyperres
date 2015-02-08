# Hyperresolution Neptunia

This is the source code for my GLIntercept (https://code.google.com/p/glintercept/) plugin for arbitrary resolution rendering support in Hyperdimension Neptunia Re;Birth 1.

I did this whole thing in a few hours, with never actually having intercepted a OpenGL game before, so it's not particularly pretty. I'm only releasing it since a few people asked for it.

What I did is start from the existing GLIntercept plugin which seemed closest to what I wanted to do (GLExtOverride) and extend it to override the functions which were required. Finally, I used the existing config file parsing support to allow users to specify their desired rendering resolution.

The most relevant code is in line 127 to 205 in ExtensionOverride.cpp

To compile this, get GLIntercept and replace the two source files in the GLExtOverride plugin with the ones in this repo.
