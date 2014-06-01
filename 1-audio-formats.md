An introduction to audio formats
=========

## Primer

*This guide is for the layperson - it is designed to help anyone get just enough information to be able to do their work. It is not a detailed technical treatise*.


Audio files are simple. Sound can be heavily compressed, gently compressed or uncompressed  (fresh out of the oven and very detailed). It needs to be supplied in the right format (of which there are hundreds) to be read and decoded by your target platform, that's all. What format you choose is dependent on what you're making, but if you run into problems sound is easy to convert (for tips on conversion, see [converting audio](4-converting-audio.md)).

## Filetypes

### Uncompressed audio (high quality)
##### Good for music, CDs, film 

Uncompressed audio is rich and detailed.

What does 'detail' mean?


My preferred format for uncompressed audio is **WAV**. It is compatible with every system (Windows, Mac, Linux) I've come across. Mac users can probably get away with AIFF too, but why take the risk when WAV is more compatible across the board. 

If you author a WAV file, it's going to be pretty large (in filesize - bigger than images, smaller than video), but sound good.


**PCM = WAV** (or AIFF)



### Compressed (lossy) audio (medium to low quality)
##### Good for games, apps, browsers - this is what most people will need


The reality is that most systems (phones, handheld gaming, the web) don't require and can't really handle rich audio. In games there are tens of sounds triggering all at once. If you plugged rich, uncompressed sound into a game environment, it's just going to fall over.


## Sample rates and bits

In addition to the file format (.WAV, .MP3 and so on), audio files contain various other layers of information which are quite important to the overall file. 
The most important of these are the **sample rate (denoted in kHz or Kilohertz)** and the **bitrate (denoted in bits i.e. 8bit, 16bit)**

*The sample and bitrate of a file is usually set when it is created. It has a large impact on the perceived quailty of the sounds (less kHz starts to sound shitty quickly). When in doubt, hunt for high sample and bitrate and [convert down](4-converting-audio.md) if necessary.*

[How do I find out what the sample rate of a file is?](5-help.md)


### Sample rates

Easy.

48kHz (or 48000 Hz) - used for film audio



  
## Further reading
[Audio file formats](http://en.wikipedia.org/wiki/Audio_file_format) *at wikipedia*


