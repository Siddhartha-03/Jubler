Welcome to XCSTest documentation!
==================================

XCS is a tool to edit text-based subtitles. It can be used as an authoring software for new subtitles or as a tool to convert, 
transform, correct and refine existing subtitles. Requires Mplayer for previewing video and Java runtime.

It supports Advanced SubStation, SubStation Alpha, SubRip. SubViewer (1 and 2), MicroDVD, MPL2 and Spruce DVD Maestro file formats, although it is easy to extend it to support other file types.
All encodings supported by Java platform are also supported here (like UTF-8). The user is able to select a list of preferred encodings in order to load the localized subtitle files.
GUI internationalization support through gettext utilities.
Styles are supported (when saving in SubStation formats). These styles are specific per subtitle or per character.
Translating mode (parent & child editors) is supported
Graphical preview of the subtitles using the FFMPEG library. Current frame, waveform preview and waveform listening is supported.
Graphically display of subtitles, which can be moved and resized.
Test and play the subtitles file using a video player (mplayer). While in playing mode the user is able to freely edit the subtitles (and inform the player for this change), add a new subtitle in real time or synchronize subtitles with the movie.
Mark subtitles with different colors, either when editing or real time when playing the video.
Spell checking, with support for dictionary selection.
Easy installation for Mac, Linux & Windows platforms and a generic :ref:`installer for all other <Testingup>` platforms (without FFMPEG support).
Auto update application.

:ref:`Key editing features <Testingupone>`
Editing individual subtitles
Splitting
Joining
Time shifting
Frame rate conversion automatically, by user request or using a free user factor
Fixing time inconsistencies such as overlapping with an optimization algorithm
Undo & redo
Cut, copy, paste, delete areas according to time & color patterns
Clear areas used for hearing impaired






















.. toctree::
   :maxdepth: 2
   :caption: Introduction

   beforeyoubegin
   howtosteps
   usermanagement

.. toctree::
   :maxdepth: 1
   :caption: Alarm Management
   :name: sec-community

   Introduction



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
