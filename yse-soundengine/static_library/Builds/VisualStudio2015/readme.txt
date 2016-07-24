
//otherwise, the juce .cpp files and all won't load
C:\repos\YSE\yse-soundengine\static_library>mklink /J JuceLibraryCode c:\repos\JUCE

//below is literal. Has to be in static_library and only there. Nowhere else matters. 
mklink /J %repos%repos\YSE\yse-soundengine\static_library\JuceLibraryCode c:\repos\JUCE

junctions need to be made to link up juce. 

